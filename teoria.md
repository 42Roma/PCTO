# Teoria

Sostituisci `<qualcosa>` con il valore che ti interessa, **anche** i simboli `<>`.

## `shell` e file system

### Vocaboli

directory | cartella

### Comandi della `shell`

| comando                              | dall'inglese            | cosa fa                                                                                                                                    |
| ------------------------------------ | ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| _Have a look around_                 |
| `pwd`                                | Print Working Directory | Stampa la cartella attuale.                                                                                                                |
| `ls`                                 | LiSt                    | Stampa la lista dei contenuti della cartella attuale. Vedi [Opzioni di `ls`](#opzioni-di-ls).                                              |
| `cd <cartella>`                      | Change Directory        | Cambia la cartella attuale. Vedi [File e cartelle speciali](#file-e-cartelle-speciali).                                                    |
| _Add and manage your stuff_          |
| `touch <file>`                       |                         | Crea un nuovo file vuoto.                                                                                                                  |
| `mkdir <cartella>`                   | MaKe DIRectory          | Crea una nuova cartella vuota.                                                                                                             |
| `mv <file/cartella> <file/cartella>` | MoVe                    | Può spostare o rinominare un file o una cartella. Vedi [Esempi `mv`](#esempi-mv).                                                          |
| `cp <file/cartella> <file/cartella>` | CoPy                    | Può copiare un file o una cartella (con l'opzione `-r`, "ricorsivo"). Utilizza la stessa sintassi di `mv`. Vedi [Esempi `mv`](#esempi-mv). |
| `rm <file>`                          | ReMove                  | Elimina il file. **Non** passa per il cestino!                                                                                             |

### File e cartelle speciali

| nome        | descrizione            |
| ----------- | ---------------------- |
| `.`         | Cartella attuale       |
| `..`        | Cartella padre         |
| `.`qualcosa | File/cartella nascosti |

### Esempi `mv`

-   file su file (rinomina)
-   file su cartella
-   cartella su cartella

### Opzioni di `ls`

| opzione | ovvero | descrizione                                     |
| ------- | ------ | ----------------------------------------------- |
| `-a`    | all    | Includi anche gli elementi che iniziano per `.` |
| `-l`    | long   | Stampa più informazioni per ogni elemento       |

## `git`

### Workflow

| comando                       | descrizione                                                |
| ----------------------------- | ---------------------------------------------------------- |
| `git add <file>`              | Aggiungi un file al pacchetto.                             |
| `git commit -m "<messaggio>"` | Chiudi il pacchetto specificando un messaggio descrittivo. |
| `git push`                    | Carica sul server tutti i pacchetti chiusi.                |

### Setup

Imposta il tuo username.

```
git config --global user.name <username>
```

Visualizza i rami locali esistenti. Quello contrassegnato da `*` è il corrente.

```
git branch
```

Crea un nuovo ramo col tuo username.

```
git branch <username>
```

Spostati su un altro ramo.

```
git checkout <ramo>
```

La prima volta che eseguirai `git push`, specifica che vuoi che venga creato un ramo con lo stesso nome anche sul server.

```
git push -u origin <ramo>
```
