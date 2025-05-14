# 📚 Extraction-based summarization
This project uses two ways to summarize `.txt` files:

1. **Word Frequencies.**
2. **TF-IDF (Term Frequency – Inverse Document Frequency).**

All this code is contained in a Jupyter Notebook.

## 🧠 Description
- **Word Frequency**: ranks words by how often they appear in the document.
- **TF-IDF**: measures how important a word is in the document relative to others.

## 🧪 Evaluation
**ROUGE (Recall-Oriented Understudy for Gisting Evaluation)** is a set of metrics used to automatically evaluate the quality of generated text by comparing it to one or more reference texts. It measures the overlap of n-grams, word sequences, and word pairs between the generated content and the reference. ROUGE is commonly used in summarization tasks, and its most used variants are:

- **ROUGE-1:** unigram (word-level) overlap
- **ROUGE-2:** bigram (two-word) overlap
- **ROUGE-L:** longest common subsequence (LCS)

Higher ROUGE scores indicate better similarity to human-written references.

## 🔗 Clone the repository
1. Clone the repository:
   ```bash
   git clone https://github.com/iAdachi/Extraction-based-summarization.git
   cd Extraction-based-summarization
   ```
2. Install dependencies:
   ```bash
   pip install nltk scikit-learn plotly numpy rouge_score
