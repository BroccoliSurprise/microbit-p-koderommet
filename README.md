# Kom i gang med micro:bit

##Steg 0 YEAH @showdialog
Først må vi koble micro:biten til PCen slik:

![Bilde av en micro:bit koblet til](https://d14xnrffmhx4ml.cloudfront.net/1662045701/veiledning-microbit-koderommet.JPG)


##Steg 1 prokkprik @showdialog
Og så skal vi koble MakeCode sammen med micro:biten, så vi kan laste ned programmer med bare ett klikk:

![Bilde av USB-connect device](https://d14xnrffmhx4ml.cloudfront.net/1662046764/veiledning-microbit-koble-sammen.gif)

##Steg 000 
Gjør som i videoen:

Trykk på det tre prikkene ved siden av "Last ned" og så "Connect Device". Trykk "NESTE, NESTE" og velg micro:bit på listen som dukker opp.

Hvis ikonet på "Last ned" ser ut som et micro:bit-ansikt i stedet for et papir-ark med en pil, har dere gjort det riktig.

Trykk på "Neste" for å fortsette.

##Steg 0 YEAH

Lag et lite program med blokker fra Basis og Inndata.

Trykk på "Last ned"-knappen i venstre hjørne for å teste.


##Steg 2232 WOO
Kjempeflott! Trykk på Slutt/Finish for å avslutte veiledningen. 

```ghost
input.onButtonPressed(Button.A, function () {
    basic.pause(100)
})
input.onGesture(Gesture.Shake, function () {
    basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        `)
    basic.showIcon(IconNames.Heart)
})
input.onSound(DetectedSound.Loud, function () {
    basic.showString("Hello!")
})
basic.forever(function () {
	
})

```