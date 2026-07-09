# Capitolo 3: Programmazione Orientata agli Oggetti (OOP) 🚀

Benvenuto nel terzo modulo del mio percorso di apprendimento in C++. Questo capitolo raccoglie tutti i progetti, gli esercizi e le architetture software incentrati sui pilastri fondamentali della programmazione a oggetti, un paradigma essenziale per lo sviluppo software moderno e l'architettura dei videogiochi.

L'obiettivo di questo modulo è stato padroneggiare la modellazione della realtà tramite codice, la protezione dei dati e la gestione efficiente della memoria dinamica.

---

## 📂 Struttura del Capitolo

Il modulo è organizzato in tre sotto-cartelle principali, ognuna focalizzata su un pilastro incrementale dell'OOP:

### 1. `🔒 basi/`
Esplora la creazione delle classi base e la protezione dei dati interni.
* **Concetti chiave:** Definizione di Classi e Oggetti, costruttori di inizializzazione.
* **Logica:** Gestione dei livelli di accesso (`public`, `private`) e isolamento degli attributi tramite metodi *Getter* e *Setter*.

### 2. `🧬 ereditarieta/`
Contiene gli esercizi dedicati al riutilizzo del codice e alla creazione di gerarchie tra classi.
* **Concetti chiave:** Relazioni tra classe Padre (Base) e classe Figlia (Derivata), parole chiave `public` e `protected`.
* **Logica:** Gestione dei costruttori a cascata con inoltro dei parametri alla classe base e riutilizzo degli attributi protetti.

### 3. `🎭 polimorfismo/`
Raccoglie le sfide più avanzate sulla gestione dinamica degli oggetti e sulle interfacce comuni.
* **Concetti chiave:** Funzioni virtuali (`virtual` e `override`), classi astratte e funzioni virtuali pure (`= 0`).
* **Memoria Dinamica:** Uso accoppiato di puntatori alla classe base, allocazione con `new`/`delete` e importanza del **distruttore virtuale** per prevenire i *memory leak*.

---

## 👑 Progetto Riassuntivo: Classe Eroe
È presente infine il "Boss Finale" del capitolo, un progetto in puro stile *RPG gaming* che unisce e sincronizza tutti i concetti appresi:
1. Creazione di una classe base astratta `Eroe` con attributi protetti e incapsulamento blindato.
2. Sviluppo delle classi derivate `Guerriero` e `Mago` con costruttori a cascata e specializzazione delle azioni.
3. Gestione di una collezione eterogenea tramite una **lista di puntatori polimorfici** (`Eroe* gilda[3]`).
4. Iterazione sui dati tramite cicli `for` e deallocazione sequenziale sicura della memoria RAM.

---

*Ogni file di codice è documentato internamente con commenti strutturati per garantire la massima leggibilità e tracciare la gestione della memoria in tempo reale.*