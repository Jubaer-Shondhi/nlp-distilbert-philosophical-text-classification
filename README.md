# Philosophy Text Classification with DistilBERT

An NLP project that classifies philosophical texts into different schools of thought using DistilBERT transformer model.

## 📋 Project Overview

This project implements a multi-class classification system to categorize philosophical content into 13 distinct categories:
- **Plato** • **Aristotle** • **Empiricism** • **Rationalism** • **Analytic Philosophy**
- **Continental Philosophy** • **Phenomenology** • **German Idealism** • **Communism**
- **Capitalism** • **Stoicism** • **Nietzsche** • **Feminism**

## 🚀 Features

- **Transformer-based Classification**: Uses DistilBERT for efficient text classification
- **Multi-class Classification**: Handles 13 philosophical categories
- **Confusion Matrix Analysis**: Detailed performance evaluation
- **Comparative Models**: Includes Random Forest classifier for comparison

## 📊 Model Performance

The DistilBERT model demonstrates strong performance in classifying philosophical texts, with particular strengths in distinguishing well-defined categories. The project includes comprehensive confusion matrix analysis showing model performance across all categories.

## 🏗️ Project Structure
PhilosophyNLPWithDistilbert/
├── PhilosophyNLPWithDistilbert.ipynb # Main Jupyter notebook
├── requirements.txt # Python dependencies
├── data/ # Dataset directory
├── models/ # Saved model files (if any)
├── images/ # Confusion matrices and results
└── README.md # This file


## ⚙️ Installation

### Prerequisites
- Python 3.7+
- pip package manager

📈 Results
The model achieves:

High accuracy for distinct philosophical categories

Understandable confusion between related philosophical schools

Robust performance across different text lengths and styles

🔍 Key Findings
Best Performing Categories: German Idealism, Capitalism, Stoicism

Common Confusions: Between related schools like Analytic vs Continental philosophy

Model Strengths: Handles nuanced philosophical terminology effectively

🤝 Contributing
Contributions are welcome! Please feel free to:

Submit pull requests

Open issues for bugs or suggestions

Suggest additional philosophical categories

Improve model architecture or preprocessing

📝 License
This project is open source. Feel free to use it for academic or personal projects.

🙏 Acknowledgments
Hugging Face for the Transformers library

Kaggle for the computational resources

Philosophical text sources and datasets used
