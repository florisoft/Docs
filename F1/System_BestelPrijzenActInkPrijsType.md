# BestelPrijzenActInkPrijsType

Voor het timer process BestelPrijzenActualiseren om de inkoopprijs van de bestelpartij over te nemen van de gevonden partijen

1. NietOvernemen, standaard niet overnemen
2. HoogstePrijs, Van de gevonden partijen de hoogste inkoopprijs overnemen
3. GemiddeldePrijs, Van de gevonden partijen de gemiddelde inkoopprijs overnemen
4. InkoopPrijsFormuleViaKalePrijs, De inkoopprijs formule laten toepassen op basis van de leverancier van de bestelpartij. Als gehanteerde bedrag gebruiken we de Kale prijs die of zojuist is berekend als dit staat ingesteld, of de bestaande kale prijs van de bestelpartij. Als bij de formule niet toegepast kan worden omdat er bijvoorbeeld geen formule is ingesteld bij de leverancier dan zullen we alsnog de hoogste inkoopprijs van de gevonden partijen overnemen als inkoopprijs 
