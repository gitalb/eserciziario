# Stringhe

## getLongest
Scrivi il metodo:

`public static String getLongest(String firstString, String secondString, String thirdString)`

Tale metodo ritorna una stringa contenente il testo della stringa più lunga tra le tre che gli sono state passate.

## isLetter
Scrivi il metodo:

`public static boolean isLetter(char c)`

Tale metodo ritorna `true` se il carattere `char` è una lettera, mentre ritorna `false` nel caso il carattere sia altro.

## isConsonant
Scrivi il metodo:

`public static boolean isConsonant(char c)`

Tale metodo ritorna `true` se il carattere `char` è una consonante, mentre ritorna `false` in tutti gli altri casi.

## isVowel
Scrivi il metodo:

`public static boolean isVowel(char c)`

Tale metodo ritorna `true` se il carattere `char` è una vocale, mentre ritorna `false` in tutti gli altri casi.

## countVowels
Scrivi il metodo:

`public static int countVowels(String text)`

Tale metodo ritorna il numero di vocali presenti nella stringa `text`.

## countConsonants
Scrivi il metodo:

`public static int countConsonants(String text)`

Tale metodo ritorna il numero di consonanti presenti nella stringa `text`.


## isAlternative
Scrivi il metodo:

`public static boolean isAlternative(String s)`

Tale metodo ritorna true se la stringa `s` contiene consonanti e vocali alternate (es. patata o cane).

## countDoubles
Scrivi il metodo:

`public static int countDoubles(String text)`

Tale metodo ritorna il numero di lettere doppie all'interno della stringa `text` (es. tutti->1, tuttti->2).

## vowelize
Scrivi il metodo:

`public static String vowelize(String text)`

Tale metodo ritorna una stringa contenente solamente le vocali della stringa `text` (es. casa->aa, purtroppo->uoo).

## camelize
Scrivi il metodo:

`public static String camelize(String text)`

Tale metodo ritorna una stringa contenente la stringa `text` formattata in stile camelCase (es. casa->CaSa, cuculo->CuCuLo).

## isAnagram
Scrivi il metodo:

`public static boolean isAnagram(String firstWord, String secondWord)`

Tale metodo ritorna `true` se `firstWord` è un anagramma di `secondWord` e viceversa; altrimenti ritorna false.

## countInString
Scrivi il metodo:

`public static int countInString(String text, char c)`

Tale metodo ritorna il numero di caratteri di tipo `c` presenti nella stringa `text`.

## Alfabeto farfallino

Scrivi la classe Java ***AlfabetoFarfallino*** che contenga due metodi utili rispettivamente per codificare e decodificare una stringa:

- `public static String codifica(String testo)`
- `public static String decodifica(String codice)`

La codifica permetterà di modificare la stringa passata aggiungendo ad ogni sillaba una "f" seguita dalla vocale della sillaba stessa. Ad esempio:

- `casa` diventerà `cafasafa`
- `canile` diventerà `cafanifilefe`
- `luccicante` diventerà `lufuccificafantefe`

La decodifica servirà per effettuare l'operazione contraria.


## Cifrario di Cesare

Da Wikipedia:

> “Il cifrario di Cesare è uno dei più antichi algoritmi crittografici di cui si abbia traccia storica. È un cifrario a sostituzione monoalfabetica in cui ogni lettera del testo in chiaro è sostituita nel testo cifrato dalla lettera che si trova un certo numero di posizioni dopo nell'alfabeto. Questi tipi di cifrari sono detti anche cifrari a sostituzione o cifrari a scorrimento a causa del loro modo di operare: la sostituzione avviene lettera per lettera, scorrendo il testo dall'inizio alla fine.” ... ” In particolare, Cesare utilizzava uno spostamento di 3 posizioni (la chiave era dunque 3” ...


Ad esempio, applicando la chiave 3: `'a'` diventa `'d'`, `'b'` diventa `'e'`, `'c'` diventa `'f'` e via dicendo:


Carattere originale  |`'a'`|`'b'`|`'c'`|`'d'`|`'e'`|...|`'x'`|`'y'`|`'z'`|
---------------------|-----|-----|-----|-----|-----|---|-----|-----|-----|
Codifica con chiave 3|`'d'`|`'e'`|`'f'`|`'g'`|`'h'`|...|`'a'`|`'b'`|`'c'`|

Applicando invece la chiave 5 `'a'` diventa `'f'`, `'b'` diventa `'g'`... eccetera:

Carattere originale  |`'a'`|`'b'`|`'c'`|`'d'`|`'e'`|...|`'x'`|`'y'`|`'z'`|
---------------------|-----|-----|-----|-----|-----|---|-----|-----|-----|
Codifica con chiave 5|`'f'`|`'g'`|`'h'`|`'i'`|`'j'`|...|`'c'`|`'d'`|`'e'`|


Scrivi la classe Java ***CifrarioDiCesare*** che contenga due metodi utili rispettivamente per codificare e decodificare una stringa:

- `public static String codifica(String testo, int chiave)`
- `public static String decodifica(String codice, int chiave)`
