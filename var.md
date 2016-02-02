# Variabili e tipi di dati

## Dichiara e assegna
Scrivere un programma contenente:
	
- la dichiarazione della variabile intera (32 bit) "intero", e assegnategli il valore esadecimale AB
- la dichiarazione della variabile intera (16 bit) "corto", e assegnategli il valore ottale 445
- la dichiarazione della variabile intera (32 bit) "intero", e assegnategli il valore decimale 111
- la dichiarazione della variabile intera (64 bit) "lungo", e assegnategli il valore decimale 222
- Stampate a terminale il nome e il valore di ognuna delle variabili dichiarate

Considera il codice che hai scritto. Quanta memoria verrà occupata per le variabili che hai dichiarato?

## PariDispari
Scrivi un programma che, dato il numero di argomenti da linea di comando (N), stampa a terminale: "N è pari" oppure "N è dispari".

## Multipli di 5
Scrivi un programma che, dato il numero di argomenti da linea di comando (N), stampa a terminale: "N è multiplo di 5" oppure "N non è multiplo di 5".

## Cornice
Scrivi un programma che scriva a terminale il tuo nome utilizzando i caratteri Unicode della pagina [U2500](http://www.unicode.org/charts/PDF/U2500.pdf). Esempio:

![](img/cornice.png)

Nota: Su alcune shell i caratteri unicode potrebbero essere rappresentati in modo errato.

## UnicodePortrait
Usa i caratteri unicode che preferisci per disegnare il tuo autoritratto. Vedi [unicode.org](http://www.unicode.org/charts/).

## MediaNote

Scrivere il programma `MediaNote` che, date 3 variabili `double nota1`, `nota2` e `nota3` (contenenti le note dei 3 test fatti in un semestre) ne calcola la media e la stampa a terminale. L'output del programma deve essere formattato nel modo seguente:

~~~text
Nota1:  1,99
Nota2:  4,69
Nota3:  4,08
------------
Media:  3,59
~~~


## CalcolaNotaInt

Scrivere un secondo programma chiamato `CalcolaNotaInt` nel quale viene dichiarata la variabile `double media` contenente la media dei 3 test calcolata da `MediaNote` e viene *arrotondata all'intero più vicino*. Ad esempio 5.4 viene approssimato a 5, mentre 5.6 viene approssimato a 6.

## CalcolaNota

Scrivere un secondo programma chiamato `CalcolaNota` nel quale viene dichiarata la variabile `double media` contenente la media dei 3 test calcolata da `MediaNote` e viene *arrotondata mezzo punto più vicino*. Ad esempio 5.4 viene approssimato a 5.5, mentre 5.77 viene approssimato a 6.

## Da frazionale ad anglosassone

Scrivi un programma nel quale vengono dichiarate due variabili `int divisore` e `dividendo`. Il programma deve poi stampare a schermo il valore della frazione in formato anglosassone. Ad esempio per `divisore = 2` e `dividendo = 1` il programma stampa 0.5.

## CPUScooter

Scrivi un programma nel quale devono essere dichiarate le seguenti variabili:

- velocità (Range: [0; 80])
- livello carburante (Range: [0; 1023])
- spiaGuastoMotore (Range: [ON; OFF])
- giriMotore (Range: [0.0; 0.99])

Dichiara le variabili scegliendo il tipo di dato più appropriato per ognuna e poi il calcola quanto spazio occupano in memoria.

## DecUni

Scrivi un programma che, dato il numero di argomenti da linea di comando (N), stampa a terminale quante *decine* e *quante* unità compongono N.

## TroncaDouble

Scrivi un programma data la variabile `double n`, ne stampa a terminale il valore *troncato* a 3 cifre decimali.
