# Pickorder Prioriteiten

Met dit timer process kan er automatisch pickorder prio bepaald worden.
Eerst activeren we de pickorders op dezelfde manier als het scherm dat doet en gebruiken we dezelfde fs2000 instellingen voor de datum van en tot.
Daarna halen we per debnr/ordnr combinatie de bijbehorende order op als deze nog niet handmatig prio heeft gekregen.
vervolgens bepalen we prioriteit aan de hand van de volgende regels:

5: De vertrektijd is verstreken en de order is volledig op locatie

4: De vertrektijd is verstreken maar nog niet alles van de order is op locatie

3: De vertrektijd is binnen het aantal ingestelde minuten vanaf nu en de order is volledig op locatie

2: Er zijn minstens het ingestelde aantal kolli op locatie en de debiteur heeft dezelfde standaard karlocatie als is ingesteld bij de timer

1: Overig
