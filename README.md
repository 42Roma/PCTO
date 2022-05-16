# PCTO

## ex00

L'utente inserisce un anno e il programma stampa se è l'anno del primo [allunaggio](https://www.google.com/search?q=allunaggio) oppure quanti anni prima o quanti anni dopo.

## ex01

L'utente inserisce un anno ed il programma verifica se l'anno inserito è [bisestile](https://www.google.com/search?q=anno+bisestile).

Qualche anno da testare:

|      |               |
| :--: | ------------- |
| 2000 | bisestile     |
| 2004 | bisestile     |
| 2001 | non bisestile |
| 1900 | non bisestile |

## ex02

L'utente inserisce un `float` (valore della temperatura) e un `char` (unità di misura). Il programma accetta valori in tre unità di misura (`C` per Celsius, `K` per Kelvin e `F` per Fahrenheit).

Se la temperatura inserita è minore dello [zero assoluto](https://www.google.com/search?q=zero+assoluto), il programma segnala un errore. Atrimenti il programma converte la tempreratura nelle altre due unità di misura e ne stampa i valori.

Inoltre, se la temperatura è valida, e il valore è minore di 15 ºC, il programma stampa `Fa freddo!`. Altrimenti se è compreso tra 15 e 25 ºC inclusi, il programma stampa `Si sta bene!`. Altrimenti stampa `Fa caldo!`.

Esempio:

```
Inserisci temperatura: 22.5 C
72.50 ºF
295.65 K
Si sta bene!
```

```
Inserisci temperatura: -283.9 C
Errore: temperatura non valida!
```

```
Inserisci temperatura: -283.9 Z
Errore: unità di misura non valida!
```

## ex03

L'utente inserisce tre numeri. Il programma controlla se possono essere le lunghezze dei lati di un triangolo (perché un triangolo possa essere tale la somma di ogni coppia lati deve essere maggiore dell'altro) e programma stampa se il triangolo è scaleno, isoscele o equilatero.

## ex04

Il programma stampa i divisori sia di 3 e che di 5 compresi tra `0` e `100` in ordine decrescente.

## ex05

L'utente inserisce due numeri interi (base e esponente). Se l'esponente è negativo, il programma stampa la potenza. Altrimenti stampa errore.

<!-- L'utente inserisce un numero intero positivo e il programma stampa il [fattoriale](https://www.google.com/search?q=fattoriale) del numero. -->

<!-- int/uint 12 -->

## ex06

L'utente inserisce un numero. Se è maggiore o uguale a 2, il programma stampa se il numero inserito è primo o non primo. Altrimenti il programma stampa un messaggio di scherno nei confronti dell'utente.

## ex07

Il programma stampa a schermo tutte le possibili coppie di due cifre decimali (0-9), **senza ripetizioni**.

Esempio:

```
00
01
02
…
09
11
…
99
```

N.B.: nella sequenza viene saltata la combinazione `10`.

## ex08

L'utente inserisce un numero intero positivo e il programma stampa il valore della [serie di Fibonacci](https://www.google.com/search?q=fibonacci) nella posizione del numero inserito dall'utente.

Esempio: L'utente inserisce `8` e il programma stampa `21`, l'ottavo numero della sequenza.

<!-- **Bonus**: Stampa un grafico della progressione, fino alla posizione inserita, stampando un `=` ogni 5 unità. -->

<!-- int/uint? 47 -->

<!-- ## workgroup00

L'utente inserisce un numero intero, seguito da un segno (`+`, `-`, `/`, `*`, `%`) e da un ultimo numero intero. Una volta inseriti i dati il programma stampa il risultato del calcolo.

Fai attenzione a controllare che le operazioni ricevute siano valide.

Esempio:

```
5 + 5
= 10
```

```
10 * 5
= 50
```

```
7 / 0
ERRORE
```

```
10 y 7
ERRORE
```

## workgroup01

L'utente inserisce un numero alla volta e il programma stampa la media di tutti i numeri inseriti fino a quel momento. Il programma si interrompe senza stampare la media quando il numero inserito è negativo.

Esempio:

```
> 5
media: 5.00
> 15
media: 10.00
> 8
media: 9.33
> -21
```

**Bonus**: Se l'utente inserisce `-42`, il programma resetta la media e stampa `La media è stata resettata!` invece di stampare la media.

## fizzbuzz

Crea un programma che stampa tutti i numeri da 1 a 100, ma:

- se il numero è divisibile per 3, stampa `fizz` al posto del numero;
- se il numero è divisibile per 5, stampa `buzz` al posto del numero.

```
1
2
fizz
4
buzz
fizz
7
8
fizz
...
13
14
fizzbuzz
...
```

## char00

Crea un programma che stampi l'alfabeto (E' obbligatorio utilizzare la tabella ASCII);

## char01

Crea un programma che stampi l'alfabeto al contrario (E' obbligatorio utilizzare la tabella ASCII);

## string00

Crea un programma che, una volta inserita una frase la stampa al contrario:

```
Inserisci una frase: Ciao a tutti!!!
!!!ittut a oaiC
```

## string01

Crea un programma che prende in input una frase e stampa a schermo la prima parola in quella frase:

```
Inserisci una frase: Ciao a tutti!!!
Ciao
```

## string02

Crea un programma che prende due argomenti, il primo è una frase, il secondo è un carattere. Il programma conterà la ricorrenza del carattere inserito all'interno della frase inserita.

```
Inserisci una frase: Benvenuto al PCTO Coding & Problem Solving
Inserisci una lettera: e
La lettera e appare 3 volte
```

```
Inserisci una frase: Che noia il coding
Inserisci una lettera: C
La lettera C appare 1 volte
``` -->
