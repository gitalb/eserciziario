#Caratteri, stringhe e Unicode

##Caratteri
###UnicodeTest
Scrivi il programma `UnicideTest` che stampa a terminale i primi 1000 caratteri unicode partendo dal primo carattere *stampabile* che è il carattere *blank* (' '). Il programma stampa il codice esadecimale e il relativo carattere:

~~~text
Char: 20 ==> ' '
Char: 21 ==> '!'
Char: 22 ==> '"'
Char: 23 ==> '#'
Char: 24 ==> '$'
Char: 25 ==> '%'
Char: 26 ==> '&'
Char: 27 ==> '''
Char: 28 ==> '('
Char: 29 ==> ')'
Char: 2a ==> '*'
Char: 2b ==> '+'
Char: 2c ==> ','
Char: 2d ==> '-'
Char: 2e ==> '.'
Char: 2f ==> '/'
Char: 30 ==> '0'
Char: 31 ==> '1'
Char: 32 ==> '2'
Char: 33 ==> '3'
Char: 34 ==> '4'
Char: 35 ==> '5'
Char: 36 ==> '6'
Char: 37 ==> '7'
Char: 38 ==> '8'
Char: 39 ==> '9'
Char: 3a ==> ':'
Char: 3b ==> ';'
Char: 3c ==> '<'
Char: 3d ==> '='
Char: 3e ==> '>'
Char: 3f ==> '?'
Char: 40 ==> '@'
Char: 41 ==> 'A'
Char: 42 ==> 'B'
Char: 43 ==> 'C'
Char: 44 ==> 'D'
Char: 45 ==> 'E'
Char: 46 ==> 'F'
Char: 47 ==> 'G'
...
Char: 37b ==> 'ͻ'
Char: 37c ==> 'ͼ'
Char: 37d ==> 'ͽ'
...
Char: 3e4 ==> 'Ϥ'
Char: 3e5 ==> 'ϥ'
Char: 3e6 ==> 'Ϧ'
Char: 3e7 ==> 'ϧ'

~~~

###Asciigator
Scrivere la classe `Asciigator` che chiede all'utente di digitare un stringa di testo e poi stampa ogni carattere contenuto nella stringa introdotta e il relativo codice Unicode (in decimale e in esadecimale). 

Ad esempio per `ABCDEF1234567890` il programma produce l'output seguente:

~~~text
Introdurre un testo:
ABCDEF1234567890

char:	'A'	'B'	'C'	'D'	'E'	'F'	'1'	'2'	'3'	'4'	'5'	'6'	'7'	'8'	'9'	'0'	
dec:	65	66	67	68	69	70	49	50	51	52	53	54	55	56	57	48	
hex:	41	42	43	44	45	46	31	32	33	34	35	36	37	38	39	30	

~~~
Mentre per `Hello world!`:

~~~text
Introdurre un testo:
Hello world!

char:	'H'	'e'	'l'	'l'	'o'	' '	'w'	'o'	'r'	'l'	'd'	'!'	
dec:	72	101	108	108	111	32	119	111	114	108	100	33	
hex:	48	65	6c	6c	6f	20	77	6f	72	6c	64	21

~~~

E per `®©™┏☂`:

~~~text
Introdurre un testo:
®©™┏☂

char:	'®'		'©'		'™'		'┏'		'☂'	
dec:	174		169		8482	9487	9730	
hex:	ae		a9		2122	250f	2602

~~~


##Codifica decodifica

###Farfallinatore
Scrivi un programma che codifichi una stringa introdotta dall'utente in *alfabeto farfallino* (se non conosci l'*alfabeto farfallino* vedi [wikipedia](https://it.wikipedia.org/wiki/Alfabeto_farfallino)). 

Esempio:

~~~text
Inserire il testo da codificare:
Tanto va la gatta al lardo
Tafantofo vafa lafa gafattafa afal lafardofo
~~~

###DeFarfallinatore
Scrivi un decodificatore capace decifrare una stringa in *alfabeto farfallino*. 

Esempio:

~~~text
Inserire il testo da decodificare:
Lefe frafagofolefe sofonofo mafatufurefe
Le fragole sono mature
~~~




