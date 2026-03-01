# NLP Projects with Transformer Architecture

A collection of Natural Language Processing (NLP) projects built using Transformer-based models. This repository covers two main use cases: sentiment analysis and chatbot evaluation.

---

## Projects

### 1. Pilkada Sentiment Analysis
**Notebook:** `Analisis Sentimen Pilkada_Transformer.ipynb`

Sentiment classification of text data related to Indonesian regional elections (Pilkada). A Transformer model (BERT or variant) is used to categorize public opinion into positive, negative, or neutral sentiment.

**Goal:** Understand public sentiment toward Pilkada-related issues from text data.

---

### 2. Chatbot Analysis & Evaluation
**Notebook:** `Transformer_Analisis Chatbot.ipynb`

A sequence-to-sequence chatbot implementation using the Transformer architecture. The notebook covers model training and fine-tuning steps, with response quality evaluated using the **ROUGE** metric (n-gram overlap between generated and reference responses).

---

## Tech Stack

- **Language:** Python 3.x
- **Deep Learning:** TensorFlow / Keras
- **NLP:** KerasNLP
- **Data Processing:** Pandas, NumPy
- **Evaluation:** rouge-score
- **Visualization:** Matplotlib, Seaborn

---

## Getting Started

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Create a virtual environment (recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate      # Linux/Mac
   .\venv\Scripts\activate       # Windows
   ```

3. **Install dependencies**
   ```bash
   pip install --upgrade pip
   pip install tensorflow pandas numpy jupyter
   pip install -U keras-nlp
   pip install rouge-score pyarrow
   ```

4. **Run the notebook**
   ```bash
   jupyter notebook
   ```
   Open the desired `.ipynb` file and run cells sequentially.
