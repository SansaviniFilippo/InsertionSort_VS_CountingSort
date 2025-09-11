# Insertion-sort vs Counting-sort

## Descrizione del progetto
Questo notebook confronta due algoritmi di ordinamento fondamentali: **Insertion Sort** e **Counting Sort**. L'obiettivo è analizzare il funzionamento, la complessità e le prestazioni di ciascun algoritmo su diversi tipi di dataset.

- **Insertion Sort**: algoritmo semplice, basato su confronti, particolarmente efficiente per piccole liste o liste quasi ordinate. Complessità nel caso peggiore: \(O(n^2)\).  
- **Counting Sort**: algoritmo non basato su confronti, ottimale per numeri interi in un intervallo limitato. Complessità: \(O(n+k)\), dove \(k\) è il valore massimo dell'array.

---

## Struttura del notebook

1. **Introduzione**
   - Panoramica sugli algoritmi e sulle differenze tra di essi.
2. **Insertion Sort**
   - Descrizione e implementazione in Python.
   - Esempio di utilizzo.
   - Analisi della complessità temporale.
3. **Counting Sort**
   - Descrizione e implementazione in Python.
   - Esempio di utilizzo.
   - Analisi della complessità temporale.
4. **Test e confronto**
   - Generazione di liste casuali, ordinate e ordinate decrescenti.
   - Misurazione dei tempi di esecuzione.
   - Visualizzazione dei risultati tramite grafici matplotlib.
