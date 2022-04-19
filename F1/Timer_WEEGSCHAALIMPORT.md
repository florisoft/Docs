Automatische weegschaal via een importbestand die er als volgt uit moet zien. 

sys. instelling WeegschaalImportPad
alle *.csv worden ingelezen, maar beter kan je maar 1 bestand neerzetten die streeds groter wordt, want fs onthoudt waar die was in die file (via sys.instelling WeegschaalImportRegelNummer)
; gescheiden
veld 0= barcode van de sticker
veld 3 = gewicht in kg

voorbeeld regel
`70000018;;;2.41`

Hier is de doos met barcode 70000018 dus 2.41kg

Handmatig systeem kan via fs-2000:vraagkilogram die net voor printen doossticker vraagt hoeveel de doos weegt
