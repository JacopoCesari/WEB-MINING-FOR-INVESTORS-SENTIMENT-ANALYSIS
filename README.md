# Stock Market News Analysis & Web/Social Media Mining

This **Web and Social Media Mining** project focuses on text analysis to examine the relationship between financial news, market indicators, and sentiment expressed on digital platforms. The analysis was conducted on articles from **Yahoo Finance** and posts/comments collected from **Nitter** (Twitter/X) and **Reddit** during the period of October 1st–20th, covering over **21,000 documents**.

## ⚙️ Techniques Adopted

### Advanced Pre-processing
**Text Cleaning**, **Lemmatization**, **Stopword Removal**, and **Vectorization** procedures were applied. **Multi-word** and **Collocation** identification was performed to enhance the quality of the analyzed text.

### Network Analysis
A **weighted co-occurrence graph** was created between the financial tickers extracted from the articles. The **Louvain algorithm** was used to identify communities of correlated assets.

### Topic Modeling
**Topic Modeling** was performed to identify the main themes, comparing results from four different algorithms: **LSA** (Latent Semantic Analysis), **NMF** (Non-negative Matrix Factorization), **LDA** (Latent Dirichlet Allocation), and **BTM** (Biterm Topic Model).

### Sentiment Analysis
Sentiment evaluation was performed using several approaches:
* **Lexicon-based Models**: **VADER** for polarity and the **NRC** model for identifying **eight basic emotions**.
* **Fine-tuned Transformer Models**: Use of **RoBERTa** and **FinBERT** (RoBERTa fine-tuned for financial text) for polarity analysis.

---

# Analisi di Notizie di Mercato e Social Media Mining

Questo progetto di **Web e Social Media Mining** si concentra sull'analisi del testo per esaminare la relazione tra notizie finanziarie, indicatori di mercato e il sentiment espresso su piattaforme digitali. L'analisi è stata condotta su articoli di **Yahoo Finance** e post/commenti raccolti da **Nitter** (Twitter/X) e **Reddit** nel periodo 1-20 ottobre, per un totale di oltre **21.000 documenti**.

## ⚙️ Tecniche Adottate

### Pre-processing Avanzato
Sono state applicate procedure di **Text Cleaning**, **Lemmatizzazione**, rimozione di **Stopwords** e **Vettorizzazione**. È stata eseguita l'identificazione di **Multi-parole** e **Collocations** per migliorare la qualità del testo analizzato.

### Network Analysis
È stato creato un **grafo pesato di co-occorrenza** tra i ticker finanziari estratti dagli articoli. Per l'identificazione delle comunità di asset correlati è stato utilizzato l'algoritmo **Louvain**.

### Topic Modeling
Per l'identificazione dei temi principali è stato eseguito il **Topic Modeling**, confrontando i risultati ottenuti da quattro diversi algoritmi: **LSA** (Latent Semantic Analysis), **NMF** (Non-negative Matrix Factorization), **LDA** (Latent Dirichlet Allocation) e **BTM** (Biterm Topic Model).

### Sentiment Analysis
La valutazione del sentiment è stata eseguita attraverso diversi approcci:
* **Modelli Lexicon-based**: **VADER** per la polarità e il modello **NRC** per l'identificazione di **otto emozioni** di base.
* **Modelli Transformer fine-tuned**: Utilizzo di **RoBERTa** e **FinBERT** (RoBERTa fine-tuned per il testo finanziario) per l'analisi di polarità.

## 👥 Team
- Botticelli Tommaso
- Cesari Jacopo
- Mugenzi Fabrice
- Zecchini Giovanni
