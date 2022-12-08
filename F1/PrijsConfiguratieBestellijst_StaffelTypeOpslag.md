# Prijsconfiguratie Staffel Type Opslag

Dit is een nieuw soort stap in de prijsconfiguraties
De voorraad stap en de bestellijst stap werken op vergelijkbare manieren.
Het idee voor deze stap is dat er een staffel ingesteld kan worden met 4 waardes die overeenkomen met de 4 prijzen waar een opslag overheen gaat door de prijsconfiguratie. De waardes van de staffel worden gekoppeld aan de prijzen volgens de onderstaande tabel.

| Staffel | Voorraad               | Bestellijst          |
|---------|------------------------|----------------------|
| Stuks   | Gebroken kolli prijs   | Gebroken kolli prijs |
| Fust    | Standaard prijs        | Standaard prijs      |
| Laag    | Minimale afnameprijs 1 | Prijs 2              |
| Kar     | Minimale afnameprijs 2 | Prijs 3              |

Doordat deze prijsconfiguratie stap maar 1 staffel opslag per keer kan toepassen is het nodig om deze stap **4** keer toe te voegen als je elke vorm van staffel eenheid wilt laten toepassen.

Welke staffel gebruikt wordt is in te geven via de debiteur toegankelijke bestellijsten/voorraden in de constanten in de nieuwe kolom Staffel Type Opslag Code, standaard is deze niet zichtbaar.
