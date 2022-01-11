# uhrzeit
#Hier wird eine Funktion definiert welche zu einer Uhrzeit eine gewisse Anzahl von Minuten dazurechnet.

def uhrzeit_minuten_addieren(stunden,minuten,summand):

    while minuten+summand >= 60:      

        stunden=stunden+1

        minuten=minuten-60

#wenn die Anzahl Minuten addiert mit dem Summand mehr als 60 ergibt, wird eine Stunde dazu gerechnet und 60 Minuten werden abgezogen.

    while stunden >= 24:

        stunden=stunden-24

    print(stunden,minuten+summand) 

#wenn die Anzahl Stunden addiert mit dem Summand über 24 beträgt, wird die Azahl Stunden wieder auf 0 zurückgesetzt.



uhrzeit_minuten_addieren(17,32,8)

uhrzeit_minuten_addieren(19,7,63)

uhrzeit_minuten_addieren(16,10,1111)
