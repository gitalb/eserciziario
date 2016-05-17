#Array e matrici



##Array monodimensionali

###Int2Day
Scrivi il programma `Int2Day` che riceve un intero come argomento da linea di comando e stampa il nome del giorno della settimana corrispondente, secondo l'associazione definita nella tabella seguente:

| **numero**         | **elemento**       |
|:--------------:|:--------------:|
|`1`               | `"lunedì"`       |
|`2`               | `"martedì"`      |
|`3`               | `"mercoledì"`    |
|`4`               | `"giovedì"`      |
|`5`               | `"venerdì"`      |
|`6`               | `"sabato"`       |
|`7`               | `"domenica"`     |

Per argomenti non appropriati o al di fuori dell'intervallo consentito, il programma stampa `"Valore non valido."`.




###TrovaMinimo
Scrivi un programma che:

1. Crea un array di interi di dimensione 100
2. Riempie l'array con 100 valori casuali compresi nell'intervallo [0; 100]
3. Stampa il contenuto dell'array
4. Trova il valore minimo contenuto nell'array
5. Stampa a terminale il minimo


###TrovaMassimo
Scrivi un programma che:

1. Crea un array di interi di dimensione 100
2. Riempie l'array con 100 valori casuali compresi nell'intervallo [-100; 0]
3. Stampa il contenuto dell'array
4. Trova il valore massimo contenuto nell'array
5. Stampa a terminale il massimo


###Media
Scrivi un programma che:

1. Crea un array di double di dimensione 50
2. Riempie l'array con 50 valori casuali compresi nell'intervallo [-10.0; 10.0]
3. Stampa il contenuto dell'array
4. Calcola la media dei valori contenuti nell'array
5. Stampa a terminale la media


##Matrici

###MinMax
Scrivi un programma che:

1. Crea un matrice di interi di dimensioni 10 x 10
2. Riempie la matrice con 100 valori casuali compresi nell'intervallo [0; 100]
3. Stampa il contenuto della matrice
4. Trova il valore massimo contenuto nella matrice
5. Trova il valore minimo contenuto nella matrice
6. Stampa a terminale il massimo e minimo

Esempio:

~~~text
14	29	59	88	21	27	14	26	
19	49	54	76	43	36	76	79	
92	71	12	63	8	85	64	43	
18	9	53	95	68	55	7	8	
97	11	37	8	5	43	2	96	
43	76	63	90	94	42	76	98	
82	91	3	81	9	48	66	32	
56	54	62	35	7	75	12	19	

Min: 2
Max: 98
~~~

### Scacchiera
Scrivi un programma che:

1. Chiede all'utente di introdurre il numero di righe e il numero di colonne di una matrice
2. Crea una matrice con le dimensioni definite dall'utente 
3. Riempie la matrice disponendo i valori `1` e `0` altrenati come su una scacchiera.

Esempio, per una matrice 5 x 5:

~~~text
Inserire numero di righe: 5
Inserire numero di colonne: 5

0 1 0 1 0 
1 0 1 0 1 
0 1 0 1 0 
1 0 1 0 1 
0 1 0 1 0
~~~

Il programma deve funzionare correttamente anche per matrici rettangolari. Esempio:

~~~text
Inserire numero di righe: 6
Inserire numero di colonne: 8

0 1 0 1 0 1 0 1 
1 0 1 0 1 0 1 0 
0 1 0 1 0 1 0 1 
1 0 1 0 1 0 1 0 
0 1 0 1 0 1 0 1 
1 0 1 0 1 0 1 0
~~~
###MatriceLRTD
Scrivi un programma che:

1. Chiede all'utente di introdurre il numero di righe e il numero di colonne di una matrice
2. Crea una matrice con le dimensioni definite dall'utente 
3. Riempie la matrice disponendo dei valori crescenti da sinistra a destra, dall'alto verso il basso.
4. Stampa lo stato della matrice

Esempio, per una matrice di 5 x 5:

~~~text
Inserire numero di righe: 5
Inserire numero di colonne: 5

0	1	2	3	4	
5	6	7	8	9	
10	11	12	13	14	
15	16	17	18	19	
20	21	22	23	24	
~~~

Il programma deve funzionare correttamente anche per matrici rettangolari. Esempio:

~~~text
Inserire numero di righe: 7
Inserire numero di colonne: 2

0	1	
2	3	
4	5	
6	7	
8	9	
10	11	
12	13	
~~~

Quando hai finito, prova a risolvere questo esercizio e i successivi *senza usare variabili di supporto* per gestire il valore crescente (usando solo le variabili `i` e `j`).

###MatriceRLTD
Ora proviamo a *ribaltare orizzontalmente* la disposizione dei valori. Scrivi un programma che:

1. Chiede all'utente di introdurre il numero di righe e il numero di colonne di una matrice
2. Crea una matrice con le dimensioni definite dall'utente 
3. Riempie la matrice disponendo dei valori crescenti da destra a sinistra, dall'alto verso il basso.
4. Stampa lo stato della matrice

Esempio, per una matrice di 5 x 5:

~~~text
Inserire numero di righe: 5
Inserire numero di colonne: 5

4	3	2	1	0	
9	8	7	6	5	
14	13	12	11	10	
19	18	17	16	15	
24	23	22	21	20	
~~~

Il programma deve funzionare correttamente anche per matrici rettangolari. Esempio:

~~~text
Inserire numero di righe: 7
Inserire numero di colonne: 2

1	0	
3	2	
5	4	
7	6	
9	8	
11	10	
13	12	
~~~

###MatriceLRDT
Ora proviamo a *ribaltare vericalmente* la disposizione dei valori. Scrivi un programma che:

1. Chiede all'utente di introdurre il numero di righe e il numero di colonne di una matrice
2. Crea una matrice con le dimensioni definite dall'utente 
3. Riempie la matrice disponendo dei valori crescenti da sinistra a destra, dal basso verso l'alto.
4. Stampa lo stato della matrice

Esempio, per una matrice di 5 x 5:

~~~text
Inserire numero di righe: 5
Inserire numero di colonne: 5

20	21	22	23	24	
15	16	17	18	19	
10	11	12	13	14	
5	6	7	8	9	
0	1	2	3	4	
~~~

Il programma deve funzionare correttamente anche per matrici rettangolari. Esempio:

~~~text
Inserire numero di righe: 7
Inserire numero di colonne: 2

12	13	
10	11	
8	9	
6	7	
4	5	
2	3	
0	1		
~~~

###MatriceRLDT
Ora proviamo a *ribaltare vericalmente e orizzontalmente* la disposizione dei valori. Scrivi un programma che:

1. Chiede all'utente di introdurre il numero di righe e il numero di colonne di una matrice
2. Crea una matrice con le dimensioni definite dall'utente 
3. Riempie la matrice disponendo dei valori crescenti da destra a sinistra, dal basso verso l'alto.
4. Stampa lo stato della matrice

Esempio, per una matrice di 5 x 5:

~~~text
Inserire numero di righe: 5
Inserire numero di colonne: 5

24	23	22	21	20	
19	18	17	16	15	
14	13	12	11	10	
9	8	7	6	5	
4	3	2	1	0	
~~~

Il programma deve funzionare correttamente anche per matrici rettangolari. Esempio:

~~~text
Inserire numero di righe: 7
Inserire numero di colonne: 2

13	12	
11	10	
9	8	
7	6	
5	4	
3	2	
1	0	
~~~

###MatriceTDLR
Ora riempire la matrice *colonna per colonna*. Scrivi un programma che:

1. Chiede all'utente di introdurre il numero di righe e il numero di colonne di una matrice
2. Crea una matrice con le dimensioni definite dall'utente 
3. Riempie la matrice disponendo dei valori crescenti dall'alto verso il basso, da sinistra a destra.
4. Stampa lo stato della matrice

Esempio, per una matrice di 5 x 5:

~~~text
Inserire numero di righe: 5
Inserire numero di colonne: 5

0	5	10	15	20	
1	6	11	16	21	
2	7	12	17	22	
3	8	13	18	23	
4	9	14	19	24	
~~~

Il programma deve funzionare correttamente anche per matrici rettangolari. Esempio:

~~~text
Inserire numero di righe: 7
Inserire numero di colonne: 2

0	2	
1	3	
2	4	
3	5	
4	6	
5	7	
6	8		
~~~