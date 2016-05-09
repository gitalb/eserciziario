# Input/Output

## Saluto
Scrivi il programma `Saluto` che, una volta avviato, chieda all'utente di inserire il proprio nome; in seguito il programma dovrà stampare a terminale `Buongiorno <nome>, bentornato!`.

~~~text
Buongiorno, inserisci il tuo nome per continuare: Luca

Buongiorno Luca, bentornato!
~~~

## ScegliNumero
Scrivi il programma `ScegliNumero` che, una volta avviato, chieda all'utente di inserire un numero compreso tra due interi positivi passati da line di comando. Il programma continuerà a chiedere un numero finchè l'utente non immetterà un valore compreso tra i due numeri interi passati in precedenza.

~~~text
java ScegliNumero 1 10

Inserisci un numero: 15
Numero non valido, riprova!

Inserisci un numero: 5
Bravo!
~~~


###IMCCalculator
Scrivi la classe `ImcCalculator` che calcola l’*indice di massa corporea* (IMC) dell’utente. L’IMC si calcola secondo la formula seguente:


![](img/IMC.png)


<!--<math display="block">
    <mi>BMI</mi>
    <mo>=</mo>
    <mfrac>
    	<mrow>
    		<mi>peso</mi>
    	</mrow>
    	<mrow>
    		<msup>
    			<mi>altezza</mi>
    			<mn>2</mn>
    		</msup>
    	</mrow>
    </mfrac>
    <mfenced open="[" close="]">
	    <mfrac>
			<mn>kg</mn>
			<msup>
				<mn>m</mn>
				<mn>2</mn>
			</msup>
	    </mfrac>
	</mfenced>
</math>-->

￼￼Il programma deve richiedere interattivamente all’utente i dati necessari per effettuare il calcolo; prima viene richiesto il nome, poi il peso espresso in kg e poi l’altezza espressa in cm.

**Nota bene**: La formula funziona solo per un peso compreso tra 20.0 e 200.0 kg e un’altezza compresa tra 140.0 e 220.0 cm; se vengono introdotti valori al di fuori di questi intervalli o valori di tipo non appropriato, il sistema chiede nuovamente il dato, fino a quando il valore è accettabile.

Alla fine il programma stampa a terminale il IMC calcolato come nell’esempio seguente:


~~~text
Questo programma calcola il tuo indice di massa corporea (IMC).
PREMI ENTER PER CONTINUARE...

Inserisci il tuo peso in kg (min: 40.0kg - max: 130.0kg): 20
Il peso deve essere compresto tra 40.0 e 130.0 kg, riprova.
Inserisci il tuo peso in kg (min: 40.0kg - max: 130.0kg): 78
Inserisci la tua altezza in cm (min: 140.0cm - max: 200.0cm): 350
l'altezza deve essere compresa tra 140.0 e 200.0 cm, riprova.
Inserisci la tua altezza in cm (min: 140.0cm - max: 200.0cm): 180
Il tuo peso: 78.0 kg
La tua altezza: 180.0 cm
Il tuo IMC: 24.074076
~~~

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
