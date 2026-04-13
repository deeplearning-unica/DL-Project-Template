# Linee Guida per la Presentazione Finale

**Corso di Deep Learning — A.A. 2025/2026**  
**Università degli Studi di Cagliari**

---

## Informazioni Generali

- **Formato**: .pptx o altro formato modificabile
- **Durata esposizione**: 10 minuti + 10 minuti di domande
- **Tutti i membri** del gruppo devono intervenire come relatori
- **Ogni membro** può ricevere domande su qualsiasi parte del progetto, incluso il codice
- Lo stile grafico è libero: scegliete un design coerente e professionale

---

## Struttura Consigliata

### Slide 1 — Titolo

Titolo del progetto, nome del gruppo, nomi dei membri, corso e anno accademico, università.

### Slide 2 — Problema e Motivazione

Presentare il problema affrontato in modo chiaro e conciso. Spiegare perché è rilevante e in quale dominio applicativo si colloca. Questa slide deve far capire immediatamente al pubblico *cosa* state facendo e *perché*.

### Slide 3 — Domande di Ricerca

Elencare le domande di ricerca (da 1 a 3) che guidano il progetto. Ogni domanda deve essere formulata in modo preciso e misurabile. Le domande devono essere il filo conduttore di tutta la presentazione: ogni slide successiva deve contribuire a rispondervi.

### Slide 4 — Dataset

Presentare il dataset utilizzato: nome, fonte, dimensione (numero di campioni, classi, dimensioni), eventuali sotto-insiemi selezionati e motivazione della scelta. Includere almeno un elemento visivo: distribuzione delle classi, esempi di campioni, o statistiche descrittive rilevanti emerse dall'analisi esplorativa.

### Slide 5 — Piano Sperimentale

Descrivere brevemente il piano sperimentale: le fasi del progetto e il protocollo di valutazione adottato (metriche, strategia di split train/val/test, baseline scelte per il confronto).

**È obbligatorio esplicitare il contributo di ciascun membro del gruppo**: chi ha lavorato su cosa e in quale sequenza temporale. Si consiglia di utilizzare un diagramma GANTT (o un grafico equivalente) che mostri sulle righe le attività o i componenti del progetto (es. preprocessing, modello generativo, classificatore, valutazione, presentazione) e sulle colonne le settimane o i periodi, indicando per ciascuna attività il nome del membro responsabile e la durata. Questo serve sia come strumento di pianificazione sia come evidenza della partecipazione attiva di tutti i componenti, aspetto che verrà considerato nella valutazione individuale.

### Slide 6 — Architettura e Approccio

Illustrare l'architettura del modello proposto. Includere un diagramma dell'architettura (es. realizzato con draw.io, Netron, o `plot_model`). Specificare: tipo di rete, componenti principali, numero di parametri, funzione di loss, ottimizzatore, learning rate, e motivare le scelte progettuali facendo riferimento ai concetti del corso.

### Slide 7 — Preprocessing e Training

Descrivere le operazioni di preprocessing applicate ai dati e le scelte relative all'addestramento: data augmentation, normalizzazione, gestione dello sbilanciamento, strategie di regolarizzazione, early stopping, salvataggio dei checkpoint. Se rilevante, mostrare snippet di codice significativi.

### Slide 8-9 — Risultati

Presentare i risultati degli esperimenti in modo strutturato. Utilizzare tabelle con le metriche di valutazione (una riga per modello/variante, una colonna per metrica) e grafici (curve di loss/accuracy, confusion matrix, confronti tra modelli). Ogni tabella e grafico deve essere commentato: cosa mostrano? Quali differenze emergono? Evidenziare i risultati migliori. Se avete condotto ablation study o confronti con baseline, includerli qui.

### Slide 10 — Discussione e Implicazioni

Rispondere esplicitamente alle domande di ricerca sulla base dei risultati ottenuti. Discutere i risultati principali: cosa funziona, cosa non funziona, e perché. Identificare le implicazioni sul contesto di riferimento (es. aspetti educativi, etici, sociali). Elencare le limitazioni dell'approccio (risorse computazionali, dimensione del dataset, generalizzabilità).

### Slide 11 — Conclusioni e Sviluppi Futuri

Riassumere in poche frasi i contributi principali del progetto. Indicare possibili sviluppi futuri: estensioni dell'architettura, dataset diversi, applicazioni reali, analisi di fairness o interpretabilità.

### Slide 12 — Riferimenti

Elencare i riferimenti bibliografici principali: paper, documentazione dei framework, fonti del dataset. Utilizzare un formato citazionale consistente.

### Slide 13 — Domande

Slide di chiusura con ringraziamento e apertura alle domande.

---

## Raccomandazioni

- **Grafici e tabelle** sono fondamentali: evitate slide con solo testo. Ogni risultato deve essere supportato visivamente.
- **Motivate ogni scelta**: non basta dire cosa avete fatto, spiegate *perché* lo avete fatto, collegandovi ai concetti del corso.
- **Siate concisi**: avete 10 minuti. Non leggete le slide, usatele come supporto visivo. Privilegiate immagini, diagrammi e dati rispetto a blocchi di testo.
- **Coerenza grafica**: scegliete una palette di colori e un font coerente e mantenetelo per tutta la presentazione.
- **Preparatevi alle domande**: tutti i membri devono conoscere ogni parte del progetto, incluso il codice. Le domande possono essere puntuali su dettagli implementativi.