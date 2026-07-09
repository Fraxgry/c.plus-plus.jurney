# 📘 C++ Corso di Programmazione - Capitolo 2: Strutture Dati e Testo

Questo archivio raccoglie tutti i concetti e gli esercizi pratici affrontati durante il secondo capitolo del percorso di apprendimento in C++. Il focus principale è stato lo spostamento da variabili singole a strutture dati complesse e dinamiche.

---

## 🛠️ Argomenti Trattati

### 1. Matrici (Vettori Bidimensionali)
* Dichiarazione e inizializzazione di matrici dinamiche usando `vector<vector<T>>`.
* Algoritmi di iterazione nidificata (doppio ciclo `for`) per la scansione e la stampa di griglie.
* Passaggio di matrici alle funzioni per riferimento (`&`) per ottimizzare le prestazioni ed evitare copie in memoria.

### 2. Stringhe e Manipolazione del Testo
* Utilizzo dell'oggetto `string` e differenza tra `cin >>` (lettura fino al primo spazio) e `getline(cin, string)` (lettura dell'intera riga).
* Accesso ai singoli caratteri tramite indicizzazione (`stringa[i]`).
* Esercizi di manipolazione avanzata (es. algoritmo per la verifica dei palindromi e censura degli spazi).

### 3. Strutture dati (`struct`)
* Creazione di tipi di dato personalizzati per aggregare variabili eterogenee.
* Uso dell'operatore punto (`.`) per l'accesso e la modifica dei membri.
* Passaggio di strutture a funzioni per riferimento per la modifica diretta dei dati (es. gestione dello sconto in un negozio d'armi).

---

## 📂 Elenco degli Esercizi Sviluppati

| File | Descrizione | Concetto Chiave |
| :--- | :--- | :--- |
| `matrice_base.cpp` | Creazione e stampa di una tabella numerica | Cicli nidificati |
| `scansione_matrice.cpp` | Ricerca di elementi specifici e conteggio dei tesori | Condizionali su griglia |
| `censura_spazi.cpp` | Sostituzione dei caratteri spazio con il simbolo `_` | Manipolazione stringhe |
| `verifica_palindromo.cpp` | Algoritmo di controllo della simmetria di una parola/frase | Vettori di caratteri e indici |
| `negozio_armi.cpp` | Modifica del prezzo di un oggetto tramite funzione | `struct` e passaggi per riferimento |
| `dungeon_completo.cpp` | **Progetto Finale**: Motore di gioco 2D interattivo con collisioni | Integrazione Matrici + Stringhe + Struct |

---

## 🏆 Progetto Finale: Daungeon&terminal
Il capitolo si conclude con un motore di gioco interattivo in cui un eroe (rappresentato da una `struct`) si muove all'interno di un labirinto (matrice), raccoglie tesori ed evita ostacoli, comandato da tastiera tramite un ciclo `do-while` e uno `switch-case`.

All'interno della cartella è presente anche un programma per il gioco tris per esplorare il gioco a turni

*Ogni file di codice è documentato internamente con docstring standard per garantire la massima leggibilità e manutenibilità.*