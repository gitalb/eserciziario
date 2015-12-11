
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



Scacchiera
