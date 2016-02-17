#Wrapper

## PariDispari
Scrivi la classe `PariDispari` che valuta il valore intero passato come argomento da linea di comando e, se il valore è pari stampa "PARI", altrimenti stampa "DISPARI". Nel caso che il valore passato non sia intero **è necessario** gestire l'eventuale errore in maniera appropriata. Qualche esempio:

~~~bash
$ java PariDispari 3
DISPARI
~~~

~~~bash
$ java PariDispari 6
PARI
~~~

~~~bash
$ java PariDispari 8
PARI
~~~


Se non vengono passati argomenti il programma termina:

~~~bash
$ java PariDispari
$
~~~

Se vengono passati argomenti non appropriati:

~~~bash
$ java PariDispari "Testo"
ERRORE: il valore Testo non è accettabile
~~~

~~~bash
$ java PariDispari 5.3
ERRORE: il valore 5.3 non è accettabile
~~~

## Hex2Dec
Scrivi la classe `Hex2Dec` che converte in decimale il valore passato come argomento da linea di comando in formato esadecimale. Nel caso che il valore passato non sia adeguato **è necessario** gestire l'eventuale errore in maniera appropriata. Esempio:

~~~bash
$ java Hex2Dec A
10
~~~

~~~bash
$ java Hex2Dec FF
255
~~~

~~~bash
$ java Hex2Dec 10
16
~~~

Se non vengono passati argomenti il programma termina:

~~~bash
$ java Hex2Dec
$
~~~

Se vengono passati argomenti non appropriati:

~~~bash
$ java Hex2Dec "EffeEffe"
ERRORE: il valore EffeEffe non è accettabile
~~~

~~~bash
$ java Hex2Dec 5.3
ERRORE: il valore 5.3 non è accettabile
~~~

## Dec2Hex
Scrivi la classe `Dec2Hex` che converte in esadecimale il valore passato come argomento da linea di comando. Nel caso che il valore passato non sia un valore decimale **è necessario** gestire l'eventuale errore in maniera appropriata. Esempio:

~~~bash
$ java Dec2Hex 10
a
~~~

~~~bash                                                                                                               
$ java Dec2Hex 255
ff
~~~

Se non vengono passati argomenti il programma termina:

~~~bash
$ java Dec2Hex
$
~~~

Se vengono passati argomenti non appropriati:

~~~bash
$ java Dec2Hex "Cento"
ERRORE: il valore Cento non è un valore decimale
~~~

~~~bash
$ java Dec2Hex 5.3
ERRORE: il valore 5.3 non è un valore decimale
~~~


## SumArgs

Scrivi la classe `SumArgs` che stampa a terminale la somma dei due valori interi passati come argomenti da linea di comando. Nel caso che i valori passati non siano valori interi **è necessario** gestire l'eventuale errore in maniera appropriata. Esempio:

~~~bash
$ java SumArgs 1 5
1 + 5 = 6
~~~

Se l'utente non inserisce uno o entrambi gli argomenti, i valori omessi vengono considerati come 0 nel calcolo della somma. Ad esempio:

~~~bash
$ java SumArgs 2
2 + 0 = 2
~~~

Oppure:

~~~bash
$ java SumArgs
0 + 0 = 0
~~~

Se vengono passati argomenti non appropriati:

~~~bash
$ java SumArgs 3 "Cinque"
ERRORE: uno o più valori passati non sono accettabili
~~~

~~~bash
$ java SumArgs "Due" 5.4
ERRORE: uno o più valori passati non sono accettabili
~~~



## SumArgsHex

Scrivi la classe `SumArgsHex` che stampa a terminale la somma dei due valori interi passati come argomenti da linea di comando in formato esadecimale. Nel caso che i valori passati non siano valori interi **è necessario** gestire l'eventuale errore in maniera appropriata. Esempio:

~~~bash
$ java SumArgsHex 5 5
5 + 5 = a
~~~

~~~bash
$ java SumArgsHex A 5
a + 5 = f
~~~

~~~bash
$ java SumArgsHex FF FF
ff + ff = 1fe
~~~

Se vengono passati argomenti non appropriati:

~~~bash
$ java SumArgsHex FF "Cinque"
ERRORE: uno o più valori passati non sono accettabili
~~~

~~~bash
$ java SumArgsHex 5.3 FF
ERRORE: uno o più valori passati non sono accettabili
~~~

# Programmi interattivi

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
