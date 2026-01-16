# NLP-Projects

A curated collection of Natural Language Processing (NLP) notebooks covering classic NLP pipelines, text classification, spam detection, chatbot workflows, and text generation experiments.

## Notebook Index

| Notebook | Focus | Highlights |
| --- | --- | --- |
| `ChatBot_Project.ipynb` | Chatbot project | End-to-end conversational workflow with NLP preprocessing and response logic. |
| `customer_service_chatbot.ipynb` | Customer service chatbot | Domain-focused chatbot experimentation and evaluation. |
| `NLP_Spam_Filtering.ipynb` | Spam detection | Text preprocessing, feature extraction, and classifier training for spam filtering. |
| `Text_Classification_Pipeline.ipynb` | Classification pipeline | Structured approach to preprocessing, vectorization, training, and evaluation. |
| `tf_idf_practice.ipynb` | TF-IDF fundamentals | Hands-on TF-IDF computation and similarity scoring exercises. |
| `Language Prediction & Text Generation.ipynb` | Language modeling | Next-word prediction and sequence generation experiments. |
| `NLP_Text_Generation_Techniques.ipynb` | Generation techniques | Multiple text generation strategies and evaluation. |
| `Read_the_News_Analysis.ipynb` | Topic/news analysis | Text analytics and summarization-oriented exploration. |

## How to Run

### Option 1: Open in Google Colab
Most notebooks include a Colab badge in the first Markdown cell. Click it to run on Colab without local setup.

### Option 2: Run Locally
1. **Create an environment** (Python 3.9+ recommended):
   ```bash
   python -m venv .venv
   source .venv/bin/activate
   ```
2. **Install common dependencies** (based on notebook imports):
   ```bash
   pip install -r requirements.txt
   ```
3. **Launch Jupyter**:
   ```bash
   jupyter notebook
   ```

> Some notebooks reference dataset helpers (e.g., codecademy-style utilities). If a notebook fails to import a dataset module, check the first cells for setup instructions or substitute local datasets.

## Reproducibility Tips

- Run cells **top to bottom** to ensure variables and preprocessing steps are defined.
- If you see download steps (e.g., `nltk.download(...)`), re-run them after environment setup.
- For best results, keep the same train/test split seeds used in the notebook when comparing metrics.

## What You’ll Demonstrate to Employers

- **NLP fundamentals**: tokenization, normalization, vectorization, and TF-IDF.
- **Machine learning workflows**: train/validation splits, model selection, and evaluation.
- **Applied problem solving**: spam detection, topic analysis, and chatbot reasoning.
- **Text generation experimentation**: sequence modeling and qualitative output checks.

If you’d like, I can also convert the notebooks into a clean, modular Python package for production-style review.
