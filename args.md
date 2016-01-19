# Argomenti da linea di comando

## HelloName
Scrivi il programma `HelloName` che stampa a terminale "Ciao &lt;nome&gt;!!". Il &lt;nome&gt; deve essere inserito come **primo argomento da linea di comando**  :

~~~text
>java HelloName Michele
Ciao Michele!!

>java HelloName Pippo
Ciao pippo!!
~~~

## HelloNames
Scrivi il programma `HelloNames` che stampa a terminale "Buongiorno &lt;cognome&gt; &lt;nome&gt;!!". Il &lt;nome&gt; deve essere inserito come **primo argomento da linea di comando**, il &lt;cognome&gt; deve essere inserito come **secondo argomento da linea di comando**:

~~~text
>java HelloNames Michele Brambilla
Buongiorno Brambilla Michele!!
~~~

## HelloAll
Scrivi il programma `HelloAll` che si comporta nel modo seguente:

- Se non vengono inseriti argomenti, stampa a terminale "Ciao a tutti!",
- Se viene inserito 1 argomento (&lt;nome&gt;), stampa "Ciao &lt;nome&gt;!!",
- Se vengono inseriti 2 argomenti (&lt;nome&gt; &lt;cognome&gt;), stampa "Buongiorno &lt;cognome&gt; &lt;nome&gt;.

~~~text
>java HelloAll Michele Brambilla
Buongiorno Brambilla Michele


>java HelloAll Michele
Ciao Michele!!


>java HelloAll 
Ciao a tutti!
~~~

## ContaArgs
Scrivi il programma `ContaArgs` che stampa a terminale il numero di argomenti inseriti da linea di comando:

~~~text
>java ContaArgs
Hai inserito 0 argomenti


>java ContaArgs a
Hai inserito 1 argomento


>java ContaArgs a b c b f d 
Hai inserito 6 argomenti
~~~

## HelloDrawing
Scrivi il programma `HelloDrawing` che funziona nel modo seguente:

- Se non vengono inseriti argomenti, disegna a terminale un quadrato,
- Se viene inserito 1 argomento stampa un triangolo,
- Se vengono inseriti 2 argomenti stampa un omino.

Ad esempio:

~~~text
>java HelloDrawing
* * *
*   *
* * * 


>java HelloDrawing a
  *
 * *
* * *

>java HelloDrawing a a
 o
/|\
/ \

~~~
