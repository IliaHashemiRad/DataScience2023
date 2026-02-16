# Course Assignments

This directory contains all computer assignments for the Foundations of Data Science course (Fall 2023). Each assignment focuses on specific data science concepts and techniques, progressing from fundamental data manipulation to advanced deep learning applications.

## 📚 Assignments Overview

### HW-01: Data Manipulation and Visualization
**Dataset**: LEGO Product Database  
**Key Topics**:
- Data loading and cleaning with Pandas
- CSV file operations and data transformations
- Exploratory Data Analysis (EDA)
- Statistical visualizations with Matplotlib and Seaborn
- Data aggregation and grouping operations

**Learning Outcomes**: Master fundamental data manipulation techniques and create informative visualizations for dataset exploration.

---

### HW-02: Statistical Methods & A/B Testing
**Dataset**: Upworthy Headlines Click-Through Data  
**Key Topics**:
- A/B testing methodology and design
- Statistical hypothesis testing
- Click-through rate (CTR) analysis
- P-values and confidence intervals
- Headline optimization strategies

**Learning Outcomes**: Understand experimental design and apply statistical tests to evaluate the effectiveness of different content variations.

---

### HW-03: Model Training & Propensity Score Matching
**Dataset**: LaLonde Job Training Program Dataset  
**Key Topics**:
- Observational studies vs. randomized experiments
- Propensity score matching for causal inference
- Treatment effect estimation
- Basic regression and classification with scikit-learn
- Model evaluation metrics

**Learning Outcomes**: Learn causal inference techniques and build predictive models to evaluate program effectiveness in non-experimental settings.

---

### HW-04: Deep Learning (4 Parts)
**Datasets**: Twitter Sentiment, Image Classification, Custom Datasets  

#### Part 1: Twitter Sentiment Analysis
- Text preprocessing and tokenization
- Neural network architecture for NLP
- Sentiment classification (positive/negative/neutral)
- Model training and validation

#### Part 2: Multi-Layer Perceptron (MLP)
- Fully connected neural networks
- Activation functions and backpropagation
- PyTorch/TensorFlow implementation
- Hyperparameter tuning

#### Part 3: Convolutional Neural Networks (CNN)
- Image classification tasks
- Convolutional layers and pooling
- Feature extraction and pattern recognition
- Model architecture design

#### Part 4: Variational Autoencoders (VAE)
- Generative modeling concepts
- Encoder-decoder architectures
- Latent space representation
- Unsupervised learning applications

**Learning Outcomes**: Gain hands-on experience with modern deep learning architectures and understand their applications in text and image analysis.

---

### HW-05: Machine Learning Classification & Web Scraping
**Website**: downloadha.com  
**Key Topics**:
- Web crawling with BeautifulSoup and Scrapy
- Data extraction from HTML pages
- Software categorization and classification
- DVC (Data Version Control) for dataset management
- End-to-end ML workflow implementation

**Learning Outcomes**: Develop practical skills in collecting real-world data through web scraping and building complete ML classification pipelines.

---

## 🔧 Technical Requirements

### Required Libraries
```bash
# Core data science
pip install pandas numpy matplotlib seaborn

# Machine learning
pip install scikit-learn

# Deep learning (HW-04)
pip install torch torchvision tensorflow keras

# Web scraping (HW-05)
pip install beautifulsoup4 requests scrapy lxml

# Additional utilities
pip install jupyter notebook ipython
```

### System Requirements
- Python 3.8 or higher
- Jupyter Notebook/JupyterLab
- Minimum 4GB RAM (8GB recommended for deep learning assignments)
- Internet connection for web scraping assignments

## 📖 How to Use

1. **Navigate to the assignment directory**
   ```bash
   cd Assignments/
   ```

2. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

3. **Open the desired assignment notebook** (e.g., `HW-01.ipynb`)

4. **Follow the instructions** within each notebook to complete the exercises

## 📊 Datasets

- **HW-01**: LEGO dataset (included or linked in notebook)
- **HW-02**: Upworthy headlines CSV (included or linked in notebook)
- **HW-03**: LaLonde dataset (available via standard ML repositories)
- **HW-04**: Twitter sentiment data and image datasets (links provided in notebooks)
- **HW-05**: Data collected via web scraping (UserAgents.txt included)

*Note: Some datasets may require downloading from external sources. Instructions are provided within each notebook.*

## 🎯 Learning Path

The assignments are designed to be completed sequentially:

1. **HW-01 → HW-02**: Build foundation in data manipulation and statistical analysis
2. **HW-03**: Progress to machine learning and causal inference
3. **HW-04**: Advance to deep learning techniques
4. **HW-05**: Apply skills to real-world data collection and ML pipelines

## 📝 Tips for Success

- **Read carefully**: Each assignment has specific requirements and evaluation criteria
- **Document your work**: Include comments and markdown explanations
- **Experiment**: Try different approaches and parameters
- **Visualize**: Create plots to understand data and model behavior
- **Validate**: Always check your results for correctness

## 🤔 Getting Help

If you encounter issues:
1. Review the course materials and lecture notes
2. Check the notebook documentation and comments
3. Consult Python/library documentation
4. Review error messages carefully for debugging clues

---

**Happy Learning! 📊🤖📈**
