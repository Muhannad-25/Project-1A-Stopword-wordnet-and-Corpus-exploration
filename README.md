# Project 1A – Stopword, WordNet, and Corpus Exploration

**Course:** Natural Language Processing (CS276B), University of Oulu  
**Instructor:** Prof. Mourad Oussalah  
**Student:** [Your Full Name]  
**Academic Year:** 2024–2025

---

## 📌 Project Summary

This project investigates the linguistic role of stopwords across several corpora and languages.  
Although stopwords are commonly removed due to their limited semantic value, this work
shows that their frequency, syntactic role, and contextual behavior may provide deeper insights
into language structure.

Ten specifications were implemented, including frequency analysis, PoS and WordNet coverage,
semantic similarity using FastText, multilingual comparison, alternative statistical measures,
co-occurrence, and sentiment-based exploration.

All evidence and outputs are included in the final report and the `artifacts/` directory.

---

## ✅ Specifications Overview

| Spec | Objective | Output | Status |
|------|-----------|--------|--------|
| 1 | Stopword frequency across corpora | Bar plots, table | ✅ Completed |
| 2 | PoS distribution + WordNet coverage + English similarity | Histogram, CSV | ✅ Completed |
| 3 | Multilingual FastText similarity | Histograms, matrices | ✅ Completed |
| 4 | Translation + Jaccard similarity across languages | Heatmap | ✅ Completed |
| 5 | Overall similarity per language | Table | ✅ Completed |
| 6 | Cross-language Jaccard | Heatmap | ✅ Completed |
| 7 | TF-IDF, Entropy, KL-Divergence comparison | Table | ✅ Completed |
| 8 | Co-occurrence networks | 5 heatmaps | ✅ Completed |
| 9 | Sentiment analysis of stopwords | Bar charts | ✅ Completed |
| 10 | Conclusion & limitations with literature discussion | Report section | ✅ Completed |

More detailed explanations are provided inside the report and corresponding notebooks.

---

## 📂 Repository Structure

```text
notebooks/
│   ├── spec1_stopwords.ipynb
│   ├── spec2_pos_wordnet.ipynb
│   ├── spec3_multilang_fasttext.ipynb
│   ├── spec4_translation_comparison.ipynb
│   ├── spec5_overall_similarity.ipynb
│   ├── spec6_crosslang_jaccard.ipynb
│   ├── spec7_alt_measures.ipynb
│   ├── spec8_stopword_connections.ipynb
│   └── spec9_sentiment.ipynb
│
artifacts/
│   ├── figures/
│   └── csv_results/
│
report/
│   └── report.pdf (or .docx)
│
requirements.txt
README.md
