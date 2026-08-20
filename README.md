# Topic Modelling and Sentiment Analysis

A comprehensive NLP project that analyzes text data through data preparation, sentiment classification, and topic discovery. Developed for IT2311 (Text Analytics), this project demonstrates end-to-end machine learning workflows for unstructured text data.

## Project Overview

This project is structured into three sequential phases:

1. **Data Preparation** — Data understanding, cleaning, and preprocessing
2. **Sentiment Classification** — Building models to predict review sentiment
3. **Topic Modelling** — Discovering latent themes and topics in the corpus

The complete analysis, model training, and evaluation workflow is contained in three Jupyter notebooks executed sequentially.

## Project Workflow

### 1. Data Preparation (`240592T_Data_Preparation.ipynb`)

- Exploratory data analysis (EDA) to understand dataset characteristics
- Data cleaning and quality assessment
- Handling missing values, duplicates, and inconsistencies
- Text normalization and preprocessing for downstream tasks
- Dataset statistics and distribution analysis

### 2. Sentiment Classification (`240592T_Sentiment_Classification.ipynb`)

- Feature extraction using vectorization techniques (TF-IDF, embeddings)
- Training supervised machine learning models for sentiment prediction
- Model evaluation using standard metrics (Accuracy, Precision, Recall, F1-Score)
- Confusion matrix and classification report analysis
- Performance comparison across multiple algorithms
- Business applications: automated review sentiment prediction

### 3. Topic Modelling (`240592T_Topic_Modelling.ipynb`)

- Latent Dirichlet Allocation (LDA) and other topic discovery methods
- Baseline model parameter tuning and optimization
- Topic coherence and interpretability analysis
- Visualization of topic distributions across documents
- Thematic insights and corpus-level pattern discovery

## Repository Structure

```
topic-modelling-and-sentiment-analysis/
├── 240592T_Data_Preparation.ipynb           # Task 1: Data cleaning & EDA
├── 240592T_Sentiment_Classification.ipynb   # Task 2: Sentiment models
├── 240592T_Topic_Modelling.ipynb            # Task 3: Topic discovery
└── README.md                                 # Project documentation
```

## Getting Started

### Requirements

- Python 3.7+
- Jupyter Notebook
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, nltk, gensim, plotly

### Running the Project

1. Clone or download the repository:
   ```bash
   git clone <repository-url>
   cd topic-modelling-and-sentiment-analysis
   ```

2. Install required dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn nltk gensim plotly
   ```

3. Execute the notebooks in order:
   - Start with `240592T_Data_Preparation.ipynb`
   - Then run `240592T_Sentiment_Classification.ipynb`
   - Finally, execute `240592T_Topic_Modelling.ipynb`

## Key Methodologies

### Text Preprocessing
- Tokenization and normalization
- Stopword removal and lemmatization
- Feature extraction (TF-IDF, word embeddings)

### Sentiment Classification
- Multiple supervised learning algorithms
- Hyperparameter tuning and model optimization
- Cross-validation and performance benchmarking
- Evaluation metrics: Accuracy, Precision, Recall, F1-Score

### Topic Modelling
- Latent Dirichlet Allocation (LDA)
- Topic coherence evaluation
- Document-topic and word-topic distributions
- Interpretable theme discovery

## Expected Outcomes

- Clean, structured dataset ready for downstream analysis
- Trained sentiment classification model for review predictions
- Discovered latent topics and thematic structure in the corpus
- Interpretable insights and visualizations for business stakeholders

## Notes

- Notebooks assume sequential execution; each builds on outputs from the previous stage
- Detailed comments and explanations are included within each notebook
- Results and model artifacts are generated during notebook execution

## Author

240592T (Nanyang Polytechnic)

## Module

IT2311: Text Analytics

---

*For questions or issues, refer to the detailed documentation within each notebook.*
