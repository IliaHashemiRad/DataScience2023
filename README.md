# Foundations of Data Science 2023

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> **Course**: Foundations of Data Science (Fall 2023)  
> **Instructor**: Dr. Khalaj  
> **Focus**: Hands-on data science techniques with real-world applications

## 📚 Overview

This repository contains comprehensive coursework for the Foundations of Data Science course, covering the complete machine learning pipeline from data exploration and statistical analysis to advanced deep learning applications. The repository includes weekly assignments and a capstone project that demonstrate practical data science skills using real-world datasets.

## 🗂️ Repository Structure

```
DataScience2023/
├── Assignments/          # Weekly homework assignments (HW-01 to HW-05)
│   ├── HW-01.ipynb      # Data Manipulation and Visualization
│   ├── HW-02.ipynb      # Statistical Methods & A/B Testing
│   ├── HW-03.ipynb      # Model Training & Propensity Score Matching
│   ├── HW-04-*.ipynb    # Deep Learning (4 parts)
│   ├── HW-05.ipynb      # ML Classification & Web Scraping
│   └── README.md        # Detailed assignment descriptions
│
└── Project/             # Capstone project on Twitter sentiment analysis
    ├── Part 1.ipynb     # Exploratory Data Analysis
    ├── Part2.ipynb      # Model Training & Classification
    ├── Part 3.ipynb     # Sentiment Analysis Pipeline
    ├── Bonus1.ipynb     # Large-scale Twitter Dataset Analysis
    ├── Bonus2.py        # Additional Analytics Script
    └── README.md        # Project documentation
```

## 🎯 Learning Objectives

This course covers essential data science concepts and techniques:

- **Data Manipulation & Visualization**: Pandas, NumPy, Matplotlib, Seaborn
- **Statistical Analysis**: Hypothesis testing, A/B testing, observational studies
- **Machine Learning**: Classification, regression, model evaluation
- **Deep Learning**: Neural networks (MLP, CNN, VAE) using PyTorch/TensorFlow
- **Natural Language Processing**: Text analysis, sentiment classification, TF-IDF
- **Web Scraping**: Data collection with BeautifulSoup and Scrapy
- **Data Version Control**: DVC for managing datasets
- **Model Deployment**: Building prediction pipelines

## 🔧 Technologies & Libraries

### Core Data Science Stack
- **Data Processing**: `pandas`, `numpy`
- **Visualization**: `matplotlib`, `seaborn`
- **Machine Learning**: `scikit-learn` (Logistic Regression, SVM, GridSearchCV)
- **Deep Learning**: `PyTorch`, `TensorFlow`, `Keras`

### Specialized Tools
- **NLP & Text**: TF-IDF vectorization, sentiment analysis
- **Web Scraping**: `BeautifulSoup`, `Scrapy`, `requests`
- **Data Management**: DVC (Data Version Control)
- **Utilities**: `googletrans`, `unidecode`, `persiantools`

## 📋 Assignments Overview

| Assignment | Topic | Key Concepts |
|-----------|-------|--------------|
| **HW-01** | Data Manipulation | LEGO dataset analysis, data cleaning, visualization |
| **HW-02** | A/B Testing | Upworthy headlines, statistical hypothesis testing |
| **HW-03** | Causal Inference | Job training programs, propensity score matching |
| **HW-04** | Deep Learning | Twitter sentiment (Part 1), MLP (Part 2), CNN (Part 3), VAE (Part 4) |
| **HW-05** | Web Scraping & ML | Software categorization, web crawling, classification |

📖 See [Assignments/README.md](Assignments/README.md) for detailed descriptions.

## 🚀 Capstone Project

**Twitter Stock Market Sentiment Analysis**

A comprehensive multi-part project analyzing sentiment in stock market-related tweets:
- Exploratory analysis of 1.6M+ tweets with company cashtags
- Building sentiment classification models (Logistic Regression, SVM)
- Creating prediction pipelines for real-time sentiment analysis
- Analyzing relationships between tweet volume and market capitalization

📖 See [Project/README.md](Project/README.md) for complete project details.

## 💻 Getting Started

### Prerequisites
```bash
Python 3.8 or higher
Jupyter Notebook or JupyterLab
```

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/IliaHashemiRad/DataScience2023.git
   cd DataScience2023
   ```

2. **Create a virtual environment** (recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install required packages**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   pip install jupyter notebook
   pip install torch tensorflow keras  # For deep learning assignments
   pip install beautifulsoup4 requests scrapy  # For web scraping
   ```

4. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

### Running the Notebooks

Navigate to the `Assignments/` or `Project/` directory and open any `.ipynb` file to explore the coursework.

## 📊 Datasets

The course utilizes diverse real-world datasets:
- **LEGO Database**: Product information and analytics
- **Upworthy Headlines**: A/B testing click-through rates
- **LaLonde Dataset**: Job training program evaluation
- **Twitter Sentiment Data**: 1.6M+ tweets with sentiment labels
- **Software Download Site**: Web-scraped application metadata

*Note: Large datasets may require separate download and are referenced within individual notebooks.*

## 📝 Documentation

Each assignment and project part includes:
- Clear problem statements
- Step-by-step implementation
- Comprehensive analysis and visualizations
- Conclusions and insights

## 🤝 Contributing

This is an educational repository for coursework. If you find issues or have suggestions for improvements, feel free to open an issue.

## 📄 License

This project is available for educational purposes. Please respect academic integrity guidelines when referencing this work.

## 👤 Author

**Ilia Hashemi Rad**

- GitHub: [@IliaHashemiRad](https://github.com/IliaHashemiRad)

## 🙏 Acknowledgments

- Dr. Khalaj for course instruction and guidance
- Course materials and datasets provided through Foundations of Data Science 2023
- Open-source community for the excellent data science tools and libraries

---

*For questions or feedback, please open an issue in this repository.*
