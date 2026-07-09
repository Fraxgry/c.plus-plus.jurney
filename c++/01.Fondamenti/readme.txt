# Capitolo 1: Fondamenti del C++ 🚀

Benvenuto nel primo modulo del mio percorso di apprendimento in C++. Questo capitolo raccoglie tutti i progetti, gli esercizi e gli algoritmi fondamentali che fanno da fondamenta per lo sviluppo software e la programmazione di videogiochi.

L'obiettivo di questo modulo è stato padroneggiare la logica di base, la gestione del flusso dei dati e la scomposizione del codice in moduli riutilizzabili.

---

## 📂 Struttura del Capitolo

Il modulo è organizzato in tre sotto-cartelle principali, ognuna focalizzata su un pilastro del linguaggio:

### 1. `📋 basi/`
Contiene i primi passi con il linguaggio e i costrutti di controllo del flusso.
* **Concetti chiave:** Variabili, tipi di dato primitivi, input/output (`cin`/`cout`).
* **Logica:** Condizioni (`if`/`else`), cicli (`for`, `while`) e validazione dell'input tramite strutture `do-while`.

### 2. `📊 liste/`
Esplora la gestione di collezioni di dati, passando dalle strutture fisse a quelle dinamiche.
* **Concetti chiave:** Array statici dello standard C e introduzione ai vettori dinamici della Standard Template Library (`std::vector`).
* **Logica:** Popolamento, manipolazione e scansione di liste di dati tramite cicli indicizzati.

### 3. `🛠️ funzioni/`
Raccoglie gli esercizi incentrati sulla modularità e sul riutilizzo del codice (DRY - Don't Repeat Yourself).
* **Concetti chiave:** Definizione di funzioni con valore di ritorno (`int`, `double`, ecc.) e funzioni di azione (`void`).
* **Ottimizzazione:** Passaggio di parametri per valore e passaggio efficiente di strutture dati complesse tramite **riferimento costante** (`const &`).

---

## 👑 Progetto Riassuntivo: finale-1 e finale-2
E' presente poi il progetto finale del capitolo. Si tratta di un simulatore in stile *gaming* che unisce tutti i concetti appresi:
1. Controllo e validazione dell'input per il numero di sessioni.
2. Allocazione dinamica dei punteggi in un `std::vector`.
3. Scomposizione del codice tramite una funzione `void` per la stampa e una funzione `int` per l'algoritmo di ricerca del punteggio massimo.
finale-2 invece gestisce un sistema di inventario utilizzando degli switch case

---

*Ogni file di codice è documentato internamente con docstring standard per garantire la massima leggibilità e manutenibilità.*