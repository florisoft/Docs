[Factuur Export - Ritplan] De Factuur - Ritplan Export functionaliteit is verder uitgebreid met het volgende:

* Systeeminstelling RitPlanVersie is uitgebreid met een nieuw versienummer: (V1_3_Met_Rekken_En_Dozen) voor het vullen van de volgende extra velden aan het .CSV exportbestand:
- Sleutelcode (debiteur losplaats veld)
- Zoekcode (debiteur debkey veld)
- Mobielnummer (debiteur debmobiel veld)
- Emailadres (debiteur email veld)
- Transnote (debiteur transnote opmerking veld)
- Aantal Rekken (het fust aantal telling o.b.v of het fust.RitplanExportType van de orderregel staat ingesteld op rekken)
- Aantal Dozen (het fust aantal telling o.b.v of het fust.RitplanExportType van de orderregel staat ingesteld op dozen)

* Voor het aantal dozen/rekken telling is het mogelijk gemaakt om per fust in de constanten deze in te stellen op ritplantype rek/doos, op het nieuwe tabblad Export.

* Ook is nieuwe systeeminstelling RitPlanExportGroepeerOrddat toegevoegd. Mitst aan worden de orderregels van de factuur gegroepeerd op orderdatum en wordt voor elke orddat groepering een aparte regel aangemaakt in het .csv exportbestand alsof deze groep een eigen 'losstaande factuur' betreft.
(201975/205265/205266)
