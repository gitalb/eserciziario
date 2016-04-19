# Stringhe

## getLongest
Scrivi il metodo:

`public static String getLongest(String firstString, String secondString, String thirdString)`

Tale metodo ritorna la stringa più lunga tra `firstString`, `secondString` e `thirdString`. Ad esempio `getLongest("lungo", "cortissimo", "corto")` ritorna `"cortissimo"`.

## countDoubles
Scrivi il metodo:

`public static int countDoubles(String text)`

Tale metodo ritorna il numero di lettere doppie all'interno della stringa `text` (es. `countDoubles("tutti")` ritorna 1, `countDoubles("tuttti")` ritorna 2).

## charCoaster
Scrivi il metodo:

`public static String charCoaster(String text)`

Tale metodo ritorna la stringa `text` trasformata alternando il caso dei caratteri (es. `charCoaster("casa")` ritorna `"cAsA"`, `charCoaster("ottovolante")` ritorna la stringa `"oTtOvOlAnTe"`).

## Phoneticyzer

Scrivi la classe `Phoneticyzer` contenente i metodi desctitti in seguito:

### isLetter
Scrivi il metodo:

`public static boolean isLetter(char c)`

Tale metodo ritorna `true` se il carattere `c` è una lettera, mentre ritorna `false` In caso contrario.

### isConsonant
Scrivi il metodo:

`public static boolean isConsonant(char c)`

Tale metodo ritorna `true` se il carattere `c` è una consonante, `false` altrimenti.

### isVowel
Scrivi il metodo:

`public static boolean isVowel(char c)`

Tale metodo ritorna `true` se `c` è una vocale, mentre ritorna `false` in tutti gli altri casi.

### countVowels
Scrivi il metodo:

`public static int countVowels(String text)`

Tale metodo ritorna il numero di vocali presenti nella stringa `text`. Ad esempio `countVowels("NOOOOOO")` ritorna 6.

### countConsonants
Scrivi il metodo:

`public static int countConsonants(String text)`

Tale metodo ritorna il numero di consonanti presenti nella stringa `text`. Ad esempio `countConsonants("NOOOOOO")` ritorna 1.

### vowelize
Scrivi il metodo:

`public static String vowelize(String text)`

Tale metodo ritorna una stringa contenente solamente le vocali della stringa `text`. Ad esempio `vowelize("casa")` ritorna `"aa"`, mentre `vowelize("lunotto")` ritorna `"uoo"`.

### isAlternative
Scrivi il metodo:

`public static boolean isAlternative(String s)`

Tale metodo ritorna true se la stringa `s` contiene consonanti e vocali alternate (es. `isAlternative("patata")` ritorna `true`).

## isAnagram
Scrivi il metodo:

`public static boolean isAnagram(String firstWord, String secondWord)`

Tale metodo ritorna `true` se `firstWord` è un anagramma di `secondWord`, altrimenti ritorna `false`. Esempio `isAnagram("calendario","locandiera")` ritorna `true`.

## countInString
Scrivi il metodo:

`public static int countInString(String text, char c)`

Tale metodo conta quante volte il carattere `c` è presente nella stringa `text`.

## Alfabeto farfallino

Il codice noto come *Alfabeto farfallino* consiste nel modificare ogni parola aggiungendo dopo ogni vocale una `f` seguita dalla vocale stessa ripetuta. Ad esempio:

- `casa` diventerà `cafasafa`
- `canile` diventerà `cafanifilefe`
- `luccicante` diventerà `lufuccificafantefe`

Scrivi la classe Java `AlfabetoFarfallino` che contenga due metodi utili rispettivamente per codificare e decodificare una stringa secondo il codice *Alfabeto Farfallino*.

- `public static String codifica(String testo)`
- `public static String decodifica(String codice)`


## Cifrario di Cesare

Da [Wikipedia](https://it.m.wikipedia.org/wiki/Cifrario_di_Cesare):

> “Il cifrario di Cesare è uno dei più antichi algoritmi crittografici di cui si abbia traccia storica. È un cifrario a sostituzione monoalfabetica in cui ogni lettera del testo in chiaro è sostituita nel testo cifrato dalla lettera che si trova un certo numero di posizioni dopo nell'alfabeto. Questi tipi di cifrari sono detti anche cifrari a sostituzione o cifrari a scorrimento a causa del loro modo di operare: la sostituzione avviene lettera per lettera, scorrendo il testo dall'inizio alla fine.” ... ” In particolare, Cesare utilizzava uno spostamento di 3 posizioni (la chiave era dunque 3” ...


Ad esempio, applicando la chiave 3: `'a'` diventa `'d'`, `'b'` diventa `'e'`, `'c'` diventa `'f'` e via dicendo:


Carattere originale  |`'a'`|`'b'`|`'c'`|`'d'`|`'e'`|...|`'x'`|`'y'`|`'z'`|
---------------------|-----|-----|-----|-----|-----|---|-----|-----|-----|
Codifica con chiave 3|`'d'`|`'e'`|`'f'`|`'g'`|`'h'`|...|`'a'`|`'b'`|`'c'`|


Applicando invece la chiave 5 `'a'` diventa `'f'`, `'b'` diventa `'g'`... eccetera:

Carattere originale  |`'a'`|`'b'`|`'c'`|`'d'`|`'e'`|...|`'x'`|`'y'`|`'z'`|
---------------------|-----|-----|-----|-----|-----|---|-----|-----|-----|
Codifica con chiave 5|`'f'`|`'g'`|`'h'`|`'i'`|`'j'`|...|`'c'`|`'d'`|`'e'`|


Scrivi la classe Java `CifrarioDiCesare` che contenga due metodi utili rispettivamente per codificare e decodificare una stringa:

- `public static String codifica(String testo, int chiave)`
- `public static String decodifica(String codice, int chiave)`
