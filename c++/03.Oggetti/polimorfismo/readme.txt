# 📂 Guida al Polimorfismo Dinamico in C++

Benvenuto in questa sezione della cartella dedicata al **Polimorfismo Dinamico**, uno dei pilastri più avanzati e potenti della Programmazione Orientata agli Oggetti (OOP) in C++. 

Questo modulo raccoglie gli esercizi e i concetti necessari per comprendere come gestire oggetti di classi differenti attraverso un'unica interfaccia comune.

---

## 🎯 Obiettivi Didattici & Contenuti della Cartella

All'interno dei file di questa cartella troverai esempi pratici che coprono i seguenti argomenti chiave:

### 1. Il Polimorfismo Dinamico (`virtual` & `override`)
* Come utilizzare i **puntatori alla classe base** per indirizzare oggetti delle classi figlie.
* Uso della parola chiave `virtual` nel Padre per abilitare il legame dinamico (*dynamic binding*).
* Uso della parola chiave `override` nelle Figlie per garantire la corretta sovrascrittura dei metodi ed evitare bug di compilazione.
* Gestione sicura della memoria dinamica (`new` e `delete`) e importanza cruciale del **distruttore virtuale** (`virtual ~ClasseBase()`) per prevenire i *memory leak*.

### 2. Funzioni Virtuali Pure & Astrazione
* Introduzione al concetto di **Classe Astratta** (classi che fungono da puro "progetto" o "stampo" e non possono essere istanziate direttamente).
* Implementazione di funzioni virtuali pure usando la sintassi `= 0`.
* Studio dell'obbligo di implementazione: come il compilatore costringe le classi figlie a definire il comportamento dei metodi astratti del padre.

### 3. Liste e Array di Puntatori Polimorfici
* Gestione di collezioni di oggetti eterogenei raggruppati sotto lo stesso tipo (es. `Veicolo* flotta[3]` o `Eroe* gilda[3]`).
* Utilizzo dei cicli `for` per automatizzare l'esecuzione di azioni polimorfiche di massa tramite l'operatore freccia (`->`).
* Cicli di pulizia automatica per deallocare correttamente la memoria RAM di tutti gli elementi della lista.

---

## 🛠️ Struttura di un Esercizio Tipo (Il Modello di Riferimento)

Ogni esercizio presente in questa cartella segue una struttura logica rigorosa, utile come schema per i tuoi progetti futuri:

1. **Definizione del Padre Astratto:** Creazione della classe base con attributi protetti/privati, distruttore virtuale e metodo `= 0`.
2. **Sviluppo delle Classi Figlie:** Ereditarietà pubblica, costruttori a cascata che passano i parametri al Padre e implementazione dei metodi con `override`.
3. **Il Main (La Collezione):** Allocazione dinamica degli oggetti all'interno di un array di puntatori, iterazione polimorfica sui dati e successiva distruzione sequenziale tramite `delete`.

---

## 🚀 Come Utilizzare questo Materiale

1. **Analizza i commenti:** Ogni file inizia con una traccia dettagliata che unisce incapsulamento, ereditarietà e polimorfismo.
2. **Sperimenta con il Debug:** Guarda come cambiano i comportamenti a runtime e osserva la liberazione degli indirizzi di memoria esadecimali stampati a schermo durante la `delete`.

*Nota: Questa cartella rappresenta il completamento dei concetti base della OOP. Assicurati di aver compreso il funzionamento dell'Ereditarietà (disponibile nel relativo README della cartella affianca) prima di dedicarti a questi esercizi.*