Timer proces tbv een automatische weegschaal om dozen te wegen via een importbestand die de weegschaal schrijf

sys. instelling WeegschaalImportPad voor het instellen waar het importbestand staat
alle bestanden met extensie .csv worden ingelezen, maar beter kan je maar 1 bestand neerzetten die streeds groter wordt, want fs onthoudt waar die was in die file (via sys.instelling WeegschaalImportRegelNummer)
bestand met ; gescheiden zijn
veld 0= barcode van de sticker
veld 3 = gewicht in kg

voorbeeld regel
`70000018;;;2.41`

Hier is de doos met barcode 70000018 dus 2.41kg

Handmatig systeem kan via fs-2000:vraagkilogram die net voor printen doossticker vraagt hoeveel de doos weegt

Gewicht wordt opgeslagen in de verpakking tabel
