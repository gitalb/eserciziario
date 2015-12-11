
#Disegno a terminale
##Figure
###ZigZag
Scrivi la classe Java `ZigZag`. Tale classe deve utilizzare il carattere '/' (*slash*) e il carattere '\' (*back-slash*) per disegnare un tratteggio verticale infinito. Il disegno deve essere realizzato esattamente come illustrato nell’esempio seguente:

~~~text
\
 \
  \
   \
   /
  /
 /
/
\
 \
  \
   \
   /
  /
 /
/
\
 \
  \
   \
   /
  /
 /
/
...
~~~

###Quadrato
Scrivi il programma Java `Quadrato`. Il programma chiede all'utente di introdurre un numero intero positivo (*N*) e poi disegna a terminale un quadrato *pieno* composto di asterischi ('*') con il lato lungo *N*:

Per *N* pari a 3 il programma stampa:

~~~text
***
***
***
~~~

Per *N* pari a 5 il programma stampa:

~~~text
*****
*****
*****
*****
*****
~~~
E via dicendo...

###QuadratoVuoto
Scrivi il programma Java `QuadratoVuoto`. Il programma funziona come il precedente `Quadrato` ma stampa solo il perimetro della figura:

Per *N* pari a 3 il programma stampa:

~~~text
***
* *
***
~~~

Per *N* pari a 5 il programma stampa:

~~~text
*****
*   *
*   *
*   *
*****
~~~
E via dicendo...

###TriangoloRettangolo
Scrivi il programma Java `TriangoloRettangolo`. Il programma chiede all'utente di introdurre un numero intero positivo (*N*) e poi disegna a terminale un quadrato composto di asterischi ('*') con l'altezza pari ad *N*:

Per *N* pari a 3 il programma stampa:

~~~text
*
** 
***
~~~

Per *N* pari a 5 il programma stampa:

~~~text
*
**
***
****
*****
~~~
E via dicendo...

###TriangoloRettangoloVuoto
Scrivi il programma Java `TriangoloRettangoloVuoto `. Il programma funziona come il precedente `TriangoloRettangolo` ma stampa solo il perimetro della figura:

Per *N* pari a 3 il programma stampa:

~~~text
*
** 
***
~~~

Per *N* pari a 5 il programma stampa:

~~~text
*
**
* *
*  *
*****
~~~
E via dicendo...

###Triangolo
Scrivi il programma Java `Triangolo`. Il programma chiede all'utente di introdurre un numero **intero positivo dispari** (*N*) e poi disegna a terminale un triangolo composto di asterischi ('*') avente la base ad *N*:

Per *N* pari a 3 il programma stampa:

~~~text
 *
***
~~~

Per *N* pari a 5 il programma stampa:

~~~text
  *
 * * 
*****
~~~
E via dicendo...

###Croce
Scrivi la classe `Croce` che disegna a terminale una croce composta di asterischi. La dimensione della croce viene definita dall’utente in modo interattivo ma accetta esclusivamente valori **numerici interi positivi pari**. Se l’utente fornisce un dato non accettabile (non numerico, dispari o negativo) il programma produce il messaggio “inserire solo numeri positivi pari” e poi ripropone la domanda.

Per *N* pari a 4 il programma stampa:

~~~text
 **
****
****
 **
~~~

Per *N* pari a 10 il programma stampa:

~~~text
     **
     **
     **
     **
 **********
 **********
     **
     **
     **
     **
~~~
E via dicendo...

###Ecorc
Scrivi la classe `Ecorc` che disegna a terminale una croce *in negativo* composta di asterischi. La dimensione della croce viene definita dall’utente in modo interattivo ma accetta esclusivamente valori **numerici interi positivi dispari**. Se l’utente fornisce un dato non accettabile (non numerico, dispari o negativo) il programma produce il messaggio “inserire solo numeri positivi pari” e poi ripropone la domanda.

Per *N* pari a 3 il programma stampa:

~~~text
* *

* * 
~~~

Per *N* pari a 5 il programma stampa:

~~~text
** **
** **

** **
** **
~~~

Per *N* pari a 7 il programma stampa:

~~~text
*** ***
*** ***
*** ***

*** ***
*** ***
*** ***
~~~
E via dicendo..

###Ics
Scrivi la classe `Ics` che disegna a terminale una X composta di asterischi. La dimensione della croce viene definita dall’utente in modo interattivo ma accetta esclusivamente valori **numerici interi positivi dispari**. Se l’utente fornisce un dato non accettabile (non numerico, dispari o negativo) il programma produce il messaggio “inserire solo numeri positivi pari” e poi ripropone la domanda.

Per *N* pari a 3 il programma stampa:

~~~text
* *
 *
* * 
~~~

Per *N* pari a 5 il programma stampa:

~~~text
*   *
 * *
  *
 * *
*   *
~~~

E via dicendo..

###Merlo
Scrivi il programma Java `Merlo`. Il programma chiede all'utente di introdurre un numero intero positivo (*N*) e poi disegna a terminale un *merlo* (elemento tipico dell'architettura militare medievale) composto di asterischi ('*') con l'altezza pari ad *N*:

Per *N* pari a 3 il programma stampa:

~~~text
*   *
** **
*****
~~~

Per *N* pari a 4 il programma stampa:

~~~text
*     *
**   **
*** ***
*******
~~~
E via dicendo...
###Tridente
Scrivi il programma Java `Tridente`. Il programma chiede all'utente di introdurre un numero intero positivo (*N*) e poi disegna a terminale un *tridente* composto di asterischi ('*') con l'altezza pari ad *N*:

Per *N* pari a 3 il programma stampa:

~~~text
* *** *** *
** ** ** **
*** * * ***
~~~

Per *N* pari a 4 il programma stampa:

~~~text
* **** **** *
** *** *** **
*** ** ** ***
**** * * ****
~~~

Per 5:

~~~text
* ***** ***** *
** **** **** **
*** *** *** ***
**** ** ** ****
***** * * *****
~~~

E via dicendo...

###TridenteSpeculare
Scrivi il programma Java `TridenteSpeculare `. Il programma chiede all'utente di introdurre un numero intero positivo (*N*) e poi disegna a terminale un *tridente* (riflesso verticalmente) composto di asterischi ('*') con l'altezza pari ad *N*:

Per *N* pari a 3 il programma stampa:

~~~text
* *** *** *
** ** ** **
*** * * ***

*** * * ***
** ** ** **
* *** *** *
~~~

Per *N* pari a 4 il programma stampa:

~~~text
* **** **** *
** *** *** **
*** ** ** ***
**** * * ****

**** * * ****
*** ** ** ***
** *** *** **
* **** **** *
~~~

Per 5:

~~~text
* ***** ***** *
** **** **** **
*** *** *** ***
**** ** ** ****
***** * * *****

***** * * *****
**** ** ** ****
*** *** *** ***
** **** **** **
* ***** ***** *
~~~

E via dicendo...

###Cerchio
Scrivi il programma `Cerchio` che chiede all'utente di introdurre un numero intero positivo (*N*) e poi disegna a terminale un *cerchio* di raggio pari ad *N*:

Per *N* pari a 2 il programma stampa:

~~~text
    * * *   
  *       * 
  *   x   * 
  *       * 
    * * * 
~~~

Per un raggio pari a 3:

~~~text
      * * *     
    *       *   
  *           * 
  *     x     * 
  *           * 
    *       *   
      * * *  
~~~

Per 7:

~~~text
            * * * * *           
        * *           * *       
      *                   *     
    *                       *   
    *                       *   
  *                           * 
  *                           * 
  *             x             * 
  *                           * 
  *                           * 
    *                       *   
    *                       *   
      *                   *     
        * *           * *       
            * * * * *   
~~~
E via dicendo...

##Animazioni 1D
Per produrre delle semplici animazioni (su di una sola riga) si deve:

1. **Disegnare** un *frame* o *fotogramma* dell'animazione (nel nostro caso, un carattere o del testo ma senza mai *andare a capo*).
2. **Aspettare** un certo tempo. Ad esempio per ottenere un *frame rate* di 10 FPS, ossia 10 immagini al secondo, dovremo attendere circa 1 decimo di secondo (100 millisecondi).
3. **Cancellare** il frame corrente (nel nostro caso, ritornare all'inizio della riga) e ripetere dal punto 1.

Per provocare l'attesa necessaria a produrre il *frame rate* desiderato è opssibile utilizzare il metodo `sleep(int ms)` della classe `Thread` specificando il tempo di attesa espresso in millisecondi:

~~~java
try {
    Thread.sleep(300);
} catch (InterruptedException ex) {
}
~~~

Per cancellare il testo scritto (il *frame precedente*) bisogna far ritornare il cursore all'inizio della riga utilizzado il comando *Carriage Return* (`\n`). Ad esempio: 

~~~java
	System.out.print("\r");
~~~


Il *ciclo di animazione* per 10 FPS sarebbe quindi:

~~~java
while(true){
	//stampa un frame
	System.out.print("???????");

	//attendi 100 ms
	try {
   		Thread.sleep(300);
	} catch (InterruptedException ex) {
	}
	System.out.print("\r");
}
~~~

Purtroppo la console di Netbeans non interpreta correttamente il codice *Carriage Return*, quindi per eseguire queste animazioni dovrete usare la shell...

###Elica
Scrivi il programma `Elica` che produce a terminale l'animazione di un elica stilizzata stampando ripetutamente la sequenza di caratteri '|','\','-','/'. Vedi il filmato:

![](/Users/andreaalbertini/Downloads/animazionitxt/elica.gif).

###Bimotore
Scrivi il programma `Bimotore ` che produce a terminale l'animazione di un aereoplano bimotore stilizzato:

![](/Users/andreaalbertini/Downloads/animazionitxt/Bimotore.gif).

###Domino
Scrivi il programma `SuperCar ` che produce l'animazione seguente:

![](/Users/andreaalbertini/Downloads/animazionitxt/Domino.gif).


###SuperCar
Scrivi il programma `SuperCar ` che produce l'animazione seguente:

![](/Users/andreaalbertini/Downloads/animazionitxt/SuperCar.gif).


SuperCar,Elica,Bimotore,Domino...

##Caratteri
UnicodeTest
TraceTable
Fibonacci, Tetranacci,Multinacci
Saludos
Scacchiera
MatriceCrescente (rigaxriga,col*col,...)
PoTre
Orologio
TrovaMinimo, TrovaMassimo
Media
MCD, mcm
Bisestili
IMCCalculator
Farfallino
GeneratoreNumeriLotto
Asciizzattore



