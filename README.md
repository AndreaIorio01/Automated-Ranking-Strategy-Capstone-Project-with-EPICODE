# 🇮🇹 Descrizione in Italiano | 🇬🇧 English Description Below 

## 🇮🇹 🧠 Sistema di Classificazione Automatica delle Strategie per i Mercati Finanziari  

### 📌 Obiettivo del Progetto
Questo progetto nasce dall’esigenza di selezionare, per ciascun mercato (ES, GC, CL, NQ), **una sola strategia tra due disponibili**, a causa di vincoli di capitale.

### ⚙️ Metodologia
L’intera analisi è stata sviluppata in **Python** e si è articolata in tre fasi principali:
- **Pulizia dei dati** provenienti da strategie pre-esistenti.
- **Costruzione di un sistema di ranking automatico** basato su parametri oggettivi:  
  _Net Profit, Max Drawdown, Avg Profit per Trade._
- **Selezione della strategia “più solida”** per ciascun mercato, utilizzando esclusivamente dati di _backtest_.

I dati elaborati sono stati poi **importati in Power BI**, dove è stato costruito un report interattivo per confrontare le performance delle strategie selezionate (Rank 1) con quelle escluse (Rank 2), nella successiva fase di _forward test_.

---

### 📈 Risultati
- Il ranking automatico ha selezionato la strategia che ha performato meglio nel **forward test in 3 mercati su 4**.
- L’**unica eccezione** è il mercato del Gold (GC), dove la strategia esclusa ha avuto una performance superiore.
- A livello di portafoglio complessivo, **Rank 1 ha prodotto un Net Profit lievemente superiore** rispetto a Rank 2.
- I **Drawdown sono simili**, ma la **stabilità dell’equity line di Rank 1 è nettamente superiore** — elemento cruciale per l’implementazione reale.

---

## 🇬🇧 🧠 Automatic Strategy Ranking System for Financial Markets 

### 📌 Project Goal
This project addresses the need to select **a single strategy among two alternatives per market** (ES, GC, CL, NQ), due to capital constraints.

### ⚙️ Methodology
The full analysis was developed in **Python**, with three main steps:
- **Cleaning strategy performance data**.
- **Designing an automatic ranking system** based on objective metrics:  
  _Net Profit, Max Drawdown, Avg Profit per Trade._
- **Selecting the “strongest” strategy** per market using _backtest-only data_.

The resulting data was then **visualized using Power BI** through an interactive report, comparing the performance of selected (Rank 1) and non-selected (Rank 2) strategies during the _forward testing_ phase.

---

### 📈 Key Findings
- The system selected the best-performing strategy in the **forward test for 3 out of 4 markets**.
- The **only exception** was Gold (GC), where the excluded strategy outperformed.
- As a portfolio, **Rank 1 produced slightly higher Net Profit** than Rank 2.
- **Drawdowns were comparable**, but **Rank 1 showed a significantly more stable equity curve** — a key aspect for real-world implementation.

---

### 📂 Contenuti del Repository / Repository Content
- `Python/`: script per pulizia dati e ranking automatico.
- `PowerBI/`: report interattivo per l’analisi.
- `README.md`: introduzione al progetto in doppia lingua.

---

### 🧑‍💻 Autore / Author
Andrea Iorio

---

