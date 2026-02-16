# Twitter Stock Market Sentiment Analysis Project

This is the capstone project for the Foundations of Data Science course (Fall 2023), focusing on analyzing sentiment in stock market-related tweets and building predictive models for financial sentiment analysis.

## 🎯 Project Overview

This comprehensive multi-part project explores the relationship between social media sentiment (specifically Twitter) and stock market behavior. Using a large-scale dataset of 1.6+ million tweets containing company cashtags, we perform exploratory analysis, build sentiment classification models, and create prediction pipelines for real-time sentiment analysis.

## 📊 Dataset

**Source**: Twitter Stock Market Sentiment Dataset  
**Size**: 1.6+ million tweets  
**Features**:
- Tweet text content
- Sentiment labels (positive, negative, neutral)
- Company cashtags (e.g., $AAPL, $TSLA, $GOOGL)
- Tweet metadata (timestamps, user information)
- Market capitalization data for companies

**Bonus Dataset**: Extended Zenodo dataset with comprehensive company, entity, and user information for large-scale analysis.

## 🗂️ Project Structure

### Part 1: Exploratory Data Analysis (EDA)
**File**: `Part 1.ipynb`

**Objectives**:
- Comprehensive dataset exploration and understanding
- Cashtag analysis and frequency distribution
- Tweet volume analysis by company
- Temporal patterns in tweet activity
- Market capitalization correlation analysis
- Visualization of key trends and patterns

**Key Insights**:
- Distribution of sentiment across different companies
- Relationship between tweet volume and market cap
- Popular companies and cashtags in the dataset
- Temporal trends in social media activity

---

### Part 2: Model Training & Classification
**File**: `Part2.ipynb`

**Objectives**:
- Data preprocessing and cleaning
- Feature engineering with TF-IDF vectorization
- Training multiple classification models
- Hyperparameter tuning with GridSearchCV
- Model evaluation and comparison

**Models Implemented**:
- Logistic Regression
- Support Vector Machine (SVM)
- Additional classifiers for comparison

**Techniques**:
- Train/validation/test split strategy
- Cross-validation for robust evaluation
- Precision, recall, F1-score metrics
- Confusion matrix analysis
- ROC curves and AUC scores

**Outcome**: Optimized sentiment classification model with strong predictive performance.

---

### Part 3: Sentiment Analysis Pipeline
**File**: `Part 3.ipynb`

**Objectives**:
- Load pre-trained sentiment classification models
- Build end-to-end prediction pipeline
- Apply sentiment analysis to new tweets
- Generate insights from predictions

**Pipeline Components**:
1. Text preprocessing and normalization
2. Feature extraction (TF-IDF)
3. Model inference and prediction
4. Result interpretation and visualization

**Applications**:
- Real-time sentiment scoring for tweets
- Company-specific sentiment tracking
- Trend analysis over time periods
- Actionable insights for stakeholders

---

### Bonus 1: Large-Scale Dataset Analysis
**File**: `Bonus1.ipynb`

**Objectives**:
- Extended analysis using Zenodo's comprehensive dataset
- Multi-dimensional exploration: companies, entities, users
- Advanced statistical analysis
- Network analysis and relationship mapping

**Additional Insights**:
- User behavior patterns and engagement metrics
- Entity recognition and categorization
- Cross-company sentiment comparisons
- Influence and reach analysis

---

### Bonus 2: Additional Analytics
**File**: `Bonus2.py`

**Description**: Python script for supplementary analysis and automated reporting.

**Features**:
- Batch processing capabilities
- Custom analytics functions
- Report generation
- Visualization exports

---

## 🔧 Technical Stack

### Core Libraries
```python
# Data processing
import pandas as pd
import numpy as np

# Visualization
import matplotlib.pyplot as plt
import seaborn as sns

# Machine Learning
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.linear_model import LogisticRegression
from sklearn.svm import SVC
from sklearn.model_selection import train_test_split, GridSearchCV
from sklearn.metrics import classification_report, confusion_matrix

# NLP
import nltk
import re
```

### Required Packages
```bash
pip install pandas numpy matplotlib seaborn
pip install scikit-learn
pip install nltk
pip install jupyter notebook
```

## 🚀 Getting Started

### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook
- Minimum 8GB RAM (for large dataset processing)
- Internet connection (for initial data download)

### Setup Instructions

1. **Navigate to the project directory**
   ```bash
   cd Project/
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt  # if available
   # or install packages individually (see Technical Stack section)
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. **Run notebooks sequentially**
   - Start with `Part 1.ipynb` for EDA
   - Proceed to `Part2.ipynb` for model training
   - Use `Part 3.ipynb` for predictions
   - Explore bonus notebooks for extended analysis

### Data Preparation

*Note: The dataset is large and may not be included in the repository.*

- Dataset download instructions are provided in `Part 1.ipynb`
- Ensure sufficient disk space (2-5GB recommended)
- Data preprocessing steps are documented in each notebook

## 📈 Key Results

### Model Performance
- **Best Model**: [Model name to be determined from Part 2]
- **Accuracy**: High-performing sentiment classification
- **F1-Score**: Balanced precision and recall
- **Use Case**: Production-ready for sentiment monitoring

### Business Insights
- Identification of sentiment patterns across major tech companies
- Correlation between social sentiment and market activity
- Actionable insights for traders and analysts
- Foundation for further research in financial NLP

## 🎓 Learning Outcomes

By completing this project, you will gain expertise in:
- Large-scale text data processing and analysis
- Feature engineering for NLP tasks
- Building and evaluating classification models
- Hyperparameter optimization techniques
- Creating production-ready ML pipelines
- Deriving business insights from model predictions
- Visualizing complex data patterns

## 📚 References

- Twitter API documentation
- Scikit-learn documentation for model selection
- Natural Language Processing techniques
- Financial sentiment analysis research papers

## 🔮 Future Enhancements

Potential extensions to this project:
- Real-time tweet streaming and analysis
- Deep learning models (LSTM, BERT) for improved accuracy
- Multi-lingual sentiment analysis
- Integration with actual stock price data
- Automated trading signal generation
- Dashboard for monitoring sentiment trends

## 🤝 Contributing

This is an educational project. Suggestions for improvements or bug reports are welcome through issues.

## 📄 License

This project is part of academic coursework and is available for educational purposes.

## 👤 Author

**Ilia Hashemi Rad**
- GitHub: [@IliaHashemiRad](https://github.com/IliaHashemiRad)

---

*For questions or feedback regarding this project, please open an issue in the repository.*
