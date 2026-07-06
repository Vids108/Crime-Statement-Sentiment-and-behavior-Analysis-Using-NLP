# Crime Statement Sentiment and Behavior Analysis Using NLP

An AI-powered Natural Language Processing (NLP) application that analyzes crime-related statements to identify sentiment and behavioral patterns. The system leverages transformer-based deep learning models to assist in understanding emotions and intent from victim, witness, and suspect statements.

---

## Project Overview

Crime statements often contain valuable emotional and behavioral cues that can support forensic investigations. Manual analysis is time-consuming and subjective. This project automates the process using NLP techniques to classify sentiment and detect behavioral intent, enabling faster and more consistent analysis.

---

## Features

- 🔍 Performs sentiment analysis (Positive, Neutral, Negative) using the RoBERTa transformer model.
- 🧠 Detects behavioral patterns such as Denial, Admission, and Defensive responses.
- 📊 Generates interactive visualizations including Word Clouds and Pie Charts.
- 📁 Produces structured CSV reports along with model evaluation metrics.

---

## Tech Stack

- Python
- Hugging Face Transformers
- RoBERTa
- PyTorch
- Pandas
- NumPy
- NLTK
- TextBlob
- Scikit-learn
- Matplotlib
- Seaborn
- WordCloud
- Jupyter Notebook
- VS Code

---

## Project Architecture

```
Crime Statements Dataset
          │
          ▼
   Data Preprocessing
          │
          ▼
 RoBERTa Sentiment Analysis
          │
          ▼
Behavior Classification
(Denial / Admission / Defensive)
          │
          ▼
Visualization & Evaluation
          │
          ▼
 Final Analysis Report
```

---

## Dataset

The project uses a structured dataset containing:

### Case Details
- Case ID
- Case Name
- Date
- Location

### Statement Details
- Case ID
- Name
- Role (Victim/Witness/Suspect)
- Gender
- Statement

---

## Installation

### Clone the repository

```bash
git clone https://github.com/your-username/Crime-Statement-Sentiment-and-behavior-Analysis-Using-NLP.git
```

### Navigate to the project

```bash
cd Crime-Statement-Sentiment-and-behavior-Analysis-Using-NLP
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the project

```bash
python main.py
```

> Replace `main.py` with your actual entry file if different.

---

## Output

The application generates:

- Sentiment Prediction
- Behavior Classification
- Word Cloud
- Pie Chart
- Confusion Matrix
- Classification Report
- CSV Analysis Report

---

## Model Performance

- Accuracy: **80%**
- Transformer Model: **RoBERTa**
- Evaluation Metrics:
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix

---

## Challenges

- Handling ambiguous crime-related language.
- Building a realistic labeled dataset.
- Combining transformer-based sentiment analysis with rule-based behavioral detection.
- Evaluating model performance on limited data.

---

## Future Scope

- AI-assisted forensic investigations.
- Legal document analysis.
- Criminal intelligence systems.
- Courtroom decision support.
- Psychological behavior assessment.
- Large-scale crime analytics.

---

## Learning Outcomes

- Implemented transformer-based NLP using Hugging Face.
- Built an end-to-end sentiment analysis pipeline.
- Performed behavior classification using Python.
- Generated analytical visualizations and reports.
- Evaluated deep learning models using standard metrics.

---

## Repository Structure

```
Crime-Statement-Sentiment-and-behavior-Analysis-Using-NLP/
│
├── dataset/
├── models/
├── outputs/
├── notebooks/
├── images/
├── main.py
├── requirements.txt
├── README.md
└── LICENSE
```

---

## Author

**Vidhi Sachdeva**

MCA Student | Software Engineer | AI & Full Stack Enthusiast

- GitHub: https://github.com/Vids108
- LinkedIn: https://www.linkedin.com/in/vidhi-sachdeva-ba1081274/

---

## License

This project is developed for academic and educational purposes. Feel free to explore, learn, and contribute by creating pull requests or opening issues.
