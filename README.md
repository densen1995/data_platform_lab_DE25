# data_platform_lab_DE25
**Using Pandas to Extract, Transform and load data. (ETL)**

- Installera och aktivera en virtual enviroment.
- Installera packages/dependencies(t.ex pandas , ipykernel) och Importera bibliotek somm behövs t.ex, pandas. Note:(ipykernel endast för jupiter notebook anvädning)
- Installera och importera matplotlib for plotting (*bonus*).

**Basically we will:**
- Read the CSV
- Clean it
- Reject impossible values and validate dataset(df_valid).
- Flag suspicious values(but can be usable)
- Generate analytics outputs/files


**Get Started**
- Ladda ner products.json: source= (Laboration 1 - Learnpoint (sti))
- Läs in Filen med Pandas read_from() metod (lägg in den i projektet först)
- Transformera innehållet så att det är användbart 

**Flagga möjliga problem såsom:**
- Saknad av ‘currency’
- produkter med extremt höga priser (kan vara ‘luxury products’)
- Kostar 0 (var den gratis? Eller problem?)
- Avvisa omöjliga värden i kolumner
- När du är klar genererar du följande filer med följande kolumner:
**analytics_summary.csv**
- snittpris
- medianpris
- antal produkter
- antal produkter med saknat pris 
**price_analysis.csv (bonus)**
- top 10 dyraste produkter
- top 10 produkter med mest avvikande pris 
**rejected_products.csv (bonus)**
- Inkludera alla produkter som är omöjliga
