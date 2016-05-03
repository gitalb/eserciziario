# Gestione degli errori

## Divisione per zero
Scrivere un programma che, dati due argomenti da linea di comando, stampi il risultato della divisione del primo arg per il secondo (utilizza numeri interi). 

Scrivi due varianti dello stesso programma utilizzando rispettivamente un blocco *try catch* e una selezione per gestire la possibile divisione per zero.

## Media note e giudizi
Scrivi la classe `Media` che accetta delle note scolastiche e/o dei giudizi e ne calcola la media. Il programma deve:
- accettare note scolastiche [1.0;6.0].
- accettare valutazioni MI (2), I (3), S (4), B (5), MB (6).
- scartare le note/valutazioni non accettabili.

## Calcolatrice2:
Riprendi il tuo codice della classe [`Calcolatrice`](metodi.md#calcolatrice) e modificalo secondo le specifiche seguenti:
- Aggiungere la gestione delle eccezioni.
- Permettere il calcolo di espressioni contenenti più operatori (es. `1 + 3 + 5`). 