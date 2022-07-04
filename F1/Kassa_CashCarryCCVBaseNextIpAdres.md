[C&C Touch - Kassa] In het betalingen scherm zijn vanaf nu de pin transacties, op het CCV Base Next pinautomaat via het ZVT Protocol, vanaf nu ondersteund via TCP connectie i.p.v dat dit voormalig verliep via CommPoort connecties.

Hiervoor zijn de volgende FSKassa instellingen aangemaakt om via TCP te kunnen verbinden:
- CashCarryCCVBaseNextIpAdres - Voor het opgeven van het IPadres van het Base Next pinautomaat.
- CashCarryCCVBaseNextPort - Voor het opgeven van poortnummer van het Base Next pinautomaat.

Het betalingen scherm zal tijdelijk disabled worden als een pinbetaling via het ZVT Protocol wordt ingediend en wacht om te worden afgehandeld. Bij het afvangen van een foutief result (timeout, abort, etc) blijft het scherm actief en vertoond een melding. Bij een succesvolle betaling via pin zal het scherm vervolgens sluiten.
(212426)
