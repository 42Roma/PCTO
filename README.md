# PCTO

## ex00

L'utente inserisce la propria età e il programma stampa se l'utente è maggiorenne o minorenne.

## ex01

L'utente inserisce due numeri e il programma stampa se il primo è multiplo del secondo.

## ex02

L'utente inserisce una temperatura in Celsius. Se la temperatura inserita è minore dello _zero assoluto_ (-273.15 ºC), il programma segnala un errore. Atrimenti il programma converte la tempreratura in Fahrenheit ed in Kelvin e stampa i valori.

Esempio:

```
Inserisci temperatura in Celsius: 22.5
72.50 ºF
295.65 K
```

```
Inserisci temperatura in Celsius: -283.9
Errore: temperatura non valida!
```

## ex03

L'utente inserisce tre numeri e il programma stampa se sono in [progressione aritmetica](https://www.google.com/search?q=progressione+aritmetica).

## ex04

L'utente inserisce un anno ed il programma verifica se l'anno inserito è [bisestile](https://www.google.com/search?q=anno+bisestile).

Qualche anno da testare:

|      |               |
| :--: | ------------- |
| 2000 | bisestile     |
| 2004 | bisestile     |
| 2001 | non bisestile |
| 1900 | non bisestile |

## ex05

L'utente inserisce tre numeri e dice se possono essere le lunghezze dei lati di un triangolo (perché un triangolo possa essere tale la somma di ogni coppia lati deve essere maggiore dell'altro).

## ex06

L'utente inserisce tre lunghezze dei lati di un triangolo. Il programma stampa se il triangolo è scaleno, isoscele o equilatero.

## ex07

L'utente inserisce un anno e il programma stampa se è l'anno del primo [allunaggio](https://www.google.com/search?q=allunaggio) oppure quanti anni prima o quanti anni dopo.

## ex08

Il programma stampa tutti i numeri tra 20 e 50 compresi.

## ex09

Il programma stampa i numeri pari compresi tra 0 e 100 in ordine decrescente.

## ex10

L'utente inserisce un numero alla volta e il programma stampa la media di tutti i numeri inseriti fino a quel momento. Il programma si interrompe senza stampare la media quando il numero inserito è negativo.

Esempio:

```
> 5
media: 5.00
> 15
media: 10.00
> 8
media: 9.33
> -42
```

**Bonus**: Se l'utente inserisce `-42`, il programma resetta la media e stampa `La media è stata resettata!` invece di stampare la media.

## bonus00

L'utente inserisce un numero. Se è maggiore o uguale a 2, il programma stampa se il numero inserito è primo o non primo. Altrimenti il programma stampa un messaggio di scherno nei confronti dell'utente.

## bonus01

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

## workgroup00

L'utente inserisce un numero, seguito da un segno (`+`, `-`, `/`, `*`, `%`) e da un ultimo numero. Una volta inseriti i dati il programma stampa il risultato del calcolo.

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

## FIZZBUZZ

Crea un programma che stampa tutti i numeri da 1 a 100:
-Qualora il numero fosse divisibile per 3, il programma stampa fizz al posto del numero;
-Qualora il numero fosse divisibile per 5, il programma stampa buzz al posto del numero;
-Qualora il numero fosse dibisibile sia per 3 che per 5, il programma stampa fizzbuzz al posto del numero.
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


## CHAR00

Crea un programma che stampi l'alfabeto (E' obbligatorio utilizzare la tabella ASCII);

## CHAR01

Crea un programma che stampi l'alfabeto al contrario (E' obbligatorio utilizzare la tabella ASCII);

## STRING00

Crea un programma che, una volta inserita una frase la stampa al contrario:
```
Inserisci una frase: Ciao a tutti!!!
!!!ittut a oaiC
```

## STRING01

Crea un programma che prende in input una frase e stampa a schermo la prima parola in quella frase:
```
Inserisci una frase: Ciao a tutti!!!
Ciao
```

## STRING02

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
```
