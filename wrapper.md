#Wrapper

## HexSum

Scrivi il programma `HexSum` che chiede all'utente di inserire due valori interi espressi in notazione **esadecimale** e poi ne stampa (sempre in base 16) il risultato della somma. Qualche esempio:

~~~text
Inserire primo addendo (in esadecimale): 9
Inserire secondo addendo (in esadecimale): 1

       9
       1 +
--------
       A
       
       
Inserire primo addendo (in esadecimale): AA55
Inserire secondo addendo (in esadecimale): 55AA

    AA55
    55AA +
--------
    FFFF
~~~

## BinSum

Scrivi il programma `BinSum` che chiede all'utente di inserire due valori interi espressi in notazione **esadecimale** e poi ne stampa la somma **in base 2**. I valori binari devono essere stampati *a 32 bit*. Qualche esempio:

~~~text
Inserire primo addendo (in esadecimale): AA
Inserire secondo addendo (in esadecimale): 5

00000000000000000000000010101010
00000000000000000000000000000101 +
--------------------------------
00000000000000000000000010101111


Inserire primo addendo (in esadecimale): 1
Inserire secondo addendo (in esadecimale): -1

00000000000000000000000000000001
11111111111111111111111111111111 +
--------------------------------
00000000000000000000000000000000
~~~

## Hex2Float
Scrivi il programma `Hex2Float` che chiede all'utente di introdurre un valore esadecimale e lo converte in un numero a virgola mobile a precisione singola (`float`). Il programma stampa i 32 bit del valore inserito e il corrispondente valore secondo il formato IEEE754. Esempio:

~~~text
Introdurre un valore esadecimale (32bit): 3fc00000
00111111110000000000000000000000 -> 1,50000


Introdurre un valore esadecimale (32bit): -7F000001
10000000111111111111111111111111 -> -2,35099e-38

Introdurre un valore esadecimale (32bit): bf800000
10111111100000000000000000000000 -> -1,00000


Introdurre un valore esadecimale (32bit): FFFFFFFF
11111111111111111111111111111111 -> NaN
~~~

Puoi verificare la bontà dei risultati ottenuti confrontandoli con quelli prodotti da [un convertitore IEEE754](http://www.h-schmidt.net/FloatConverter/IEEE754.html).
