# Progetto di Linguistica Computazionale (A.A. 2025/26)

Progetto per l'esame di **Linguistica Computazionale**, Corso di Laurea in Informatica Umanistica, Università di Pisa.

**Autrice:** Chiara Giordano  
**Docenti:** Prof. Alessandro Lenci, Dott. Alessandro Bondielli  

---

## Descrizione del Progetto

Il progetto ha lo scopo di analizzare ed estrarre informazioni linguistiche da due corpora in lingua inglese attraverso la libreria `NLTK` e strumenti di Natural Language Processing in Python.

### Corpora Analizzati:
1. **Corpus 1 (`Corpora_1.txt`)**: Prosa letteraria — Estratto da *Pride and Prejudice* di Jane Austen.
2. **Corpus 2 (`Corpora_2.txt`)**: Saggistica/Articoli scientifici — Selezione di articoli accademici in ambito psicologico.

---

## Struttura del Repository

* `Programma_1.ipynb`: Notebook Jupyter contenente il confronto statistico e linguistico completo tra i due corpora (lunghezze medie, distribuzione PoS, TTR incrementale, lemmi per frase, classificazione di polarità Naive Bayes e polarità del documento).
* `Programma_2_Corpus1.ipynb`: Estrazione di informazioni dal Corpus 1 (Top-50 sostantivi/verbi/aggettivi, n-grammi di parole e PoS, collocazioni Aggettivo+Sostantivo con MI/LMI, analisi frasi con modelli di Markov di ordine 3, stopwords, pronomi e Named Entity Recognition con LMI).
* `Programma_2_Corpus2.ipynb`: Estrazione delle medesime informazioni e analisi sul Corpus 2.
* `Corpora_1.txt` & `Corpora_2.txt`: I due file di testo UTF-8 che costituiscono i corpora di analisi.
* `movie_reviews/`: Dataset locale di recensioni di film utilizzato per l'addestramento del classificatore Multinomial Naive Bayes con TF-IDF per l'analisi di polarità.

---

## Requisiti e Dipendenze

Per eseguire i notebook è necessario un ambiente Python 3 con le seguenti librerie:

```bash
pip install nltk scikit-learn