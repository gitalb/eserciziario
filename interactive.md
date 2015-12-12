#Programmi interattivi

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
￼￼
Il programma deve richiedere interattivamente all’utente i dati necessari per effettuare il calcolo; prima viene richiesto il nome, poi il peso espresso in kg e poi l’altezza espressa in cm.

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