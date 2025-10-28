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
🔧 Installation & Setup
Python ≥ 3.8 is required.

Install dependencies:

bash
Copy code
pip install -r requirements.txt
Download NLTK corpora before running:

python
Copy code
import nltk
nltk.download('all')
▶️ How to Run
Launch notebooks one by one:

bash
Copy code
jupyter notebook notebooks/spec1_stopwords.ipynb
Each notebook automatically exports:

CSV files → artifacts/csv_results/

Figures & heatmaps → artifacts/figures/

📊 Results Snapshot
Stopwords represent ~40–50% of high-frequency words across English corpora

Most stopwords are grammatical function words

44% of English stopwords appear in WordNet

Multilingual similarity varies by morphology and language family

Alternative measures confirm: frequency alone is insufficient

Stopwords mostly appear in neutral sentences

Full analysis and all figures are included in the report.

📚 References
S. Sarica and J. Luo, “Stopwords in technical language processing,” PLOS ONE, 2021.

NLTK Corpora & Official Documentation

Facebook AI Research — FastText Word Embeddings

📬 Contact
For questions or feedback:
mumahdi25@student.oulo.fi
