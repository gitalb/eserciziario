# Metodi

## circonferenza
Scrivi il metodo:

`public static double calcolaCirconferenza(double raggio)`

Tale metodo ritorna un numero che rappresenta la circonferenza di un cerchio di raggio `raggio`.

## areaTriangolo
Scrivi il metodo:

`public static double calcolaAreaTriangolo(double base, double altezza)`

Tale metodo ritorna un numero che rappresenta l' area di un triangolo di base `base` e di altezza `altezza`.


## Trenino
Scrivi la classe Trenino che contiene i seguenti metodi:

`public static void stampaLocomotiva()`

`public static void stampaPasseggeriPiccolo()`

`public static void stampaPasseggeriGrande()`

`public static void stampaMerciPiccolo()`

`public static void stampaMerciGrande()`

`public static void stampaGancio()`

Richiama i metodi in maniera da comporre un treno utilizzando a piacimento i vagoni creati tramite i metodi, come ad esempio (Locomotiva, PasseggeriPiccolo, MerciGrande):

```

   /T\
  /|||\
  | O |
  LLLLL
  LLLLL
    |
  PPPPP
  P   P
  PPPPP
    |
  MMMMM
  M   M
  M   M
  M   M
  MMMMM
  
```

## MCD
Scrivi il metodo:

`public static int calcolaMCD(int a, int b)`

Tale metodo ci permetterà di calcolare il Massimo comun divisore di 2 numeri. ([Wiki: MCD](https://it.wikipedia.org/wiki/Massimo_comun_divisore))

## mcm
Scrivi il metodo:

`public static int calcolaMcm(int a, int b)`

Tale metodo ci permetterà di calcolare il minimo comune multiplo di 2 numeri. ([Wiki: mcm](https://it.wikipedia.org/wiki/Minimo_comune_multiplo))



## calcolatrice
Scrivi il metodo:

`public static int calcola(int a, int b, char operatore)`

Tale esegue un'operazione matematica di base sui due numeri `a` e `b`. Il valore `operatore` (`'+'`, `'-'`, `'*'`, `'/'`) definisce l'operazione da eseguire. Ad esempio l'invocazione `calcola(5,2,'+')` ritornerà 7 (5+2) mentre l'invocazione `calcola(5,2,'*')` ritornerà 10 (5*2). Se il parametro `operatore` contiene un carattere non valido, il metodo ritorna 0.



## repeat
Scrivi il metodo:

`public static String repeat(String text, int times)`

Tale metodo ritorna una stringa contenente il testo `text` ripetuto `times` volte. Ad esempio l'invocazione `repeat("X",5)` ritorna la stringa `XXXXX`.

Ora utilizza il metodo `repeat` per produrre il disegno seguente:

~~~text
----****
----****
----****
----****
****----
****----
****----
****----
~~~

Quante righe di codice hai scritto? Una dovrebbe bastare...

## longest

Scrivi il metodo:

`public static String longest(String a, String b)`

che ritorna la stringa più lunga tra `a`, `b`.

Ad esempio `longest("cane","gatto")` ritorna la stringa `gatto`, mentre `longest("abcdef","gatto")` ritorna `abcdef`.

## alternate

Scrivi il metodo:

`public static String alternate(String a, String b, int times)`

Il metodo ritorna una stringa di testo contenente le stringhe `a` e `b` alternate `times` volte. Ad esempio `alternate("*","-",5)` ritorna la stringa `*-*-*-*-*-`, mentre `alternate("va","Ja",2)` ritorna la stringa `vaJavaJa`.


## concatenate

Scrivi il metodo:

`public static String concatenate(int a, int b, int c, char separator, char terminator)`

che ritorna una stringa contenente l'elenco dei valori dei parametri `a`, `b` e `c`. I valori sono separati dal carattere `separator` e la lista è terminata dal carattere `terminator`.

Ad esempio `concatenate(1,2,3,';','.')` ritorna la stringa `1;2;3.`, mentre `concatenate(10,20,30,'_','!')` ritorna la stringa `10_20_30!`.

boolean crescenti(int a, int b, int c)
Ritorna true se a, b e c sono ordinati dal più piccolo al più grande.

##toLower 
Scrivi il metodo `char toLower(char c)` che, se `c` è un carattere alfabetico maiuscolo, ritorna il corrispondente carattere minuscolo. Altrimenti ritorna c. 

Ad esempio:

- `toLower('A')` ritorna `'a'` 
- `toLower('b')` ritorna `'b'`
- `toLower(';')` ritorna `';'`

## sortCharacters

Implementa il metodo `String sortCharacters(char a, char b, char c)` che ritorna una stringa contenente i caratteri `a`, `b` e `c` disposti in ordine alfabetico e separati da una virgola. Nell'ordinamento, il caso dei caratteri alfabetici deve essere ignorato (`'a'` e `'A'`, hanno lo stesso ordine). Qualche esempio:

- `sortCharacters('c','A','b')` ritorna la stringa `"A,b,c"`,
- `sortCharacters('M','m','G')` ritorna la stringa `"G,M,m"`.

## blackjackWinner

Nel Blackjack vince il giocatore che totalizza un punteggio che sia il più vicino possibile, ma non superi, il valore 21. Scrivi il metodo `int blackjackWinner(int score1, int score2)`che, dati due punteggi (nel range [1, 21]) `score1` e `score2`, ritorna un numero intero secondo le seguenti regole:

- in caso di pareggio, ritorna `0`
- se vince `score1` ritorna `1`
- se vince `score2` ritorna `2`


## sommaUnivoca

Scrivi il metodo:

`int sommaUnivoca(int a, int b, int c)`

Tale metodo ritorna la somma di `a`, `b` e `c` ma i valori duplicati vengono tralasciati nel calcolo del totale. Ad esempio `sommaUnivoca(1,2,3)` ritorna `6` mentre `sommaUnivoca(1,2,1)` ritorna `3`.

# sommaTonda

Scrivi il metodo `int sommaTonda(int a, int b, int c)` che ritorna la somma di `a`, `b` e `c` arrotondata al multiplo di 10 più vicino.

## getDigits
Scrivi il metodo `int getDigits(int n)` che ritorna il numero digits (cifre) necessario per la rappresentazione decimale di `n`. Ad esempio `getDigits(11)` ritorna `2` mentre `getDigits(12435)` ritorna `5`.



