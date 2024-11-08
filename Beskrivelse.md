# Trekk på kode for å få motoren til å spinne

## Åpne motorblokken
Bruk ulik kode for å gjøre dette
Bruk blokken ``||basic:pause||`` og blokken ``||servos:setAngle||`` og plasser dem i ``||basic:forever|| blokken``.
```blocks
basic.forever(function () {
servos.P0.setAngle(90)
basic.pause(100)
```
## Endre på verdiene for vinkel og pause
Prøv å få motoren til å gå fra 0 til 180
```blocks
servos.P0.setAngle(0)
servos.P0.setAngle(180)
```
## Ferdig kode
```blocks
basic.forever(function () {
        servos.P0.setAngle(30)
        basic.pause(1000)
        servos.P0.setAngle(150)
        basic.pause(1000)
```