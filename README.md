<p align="center">
  <img src="https://img.shields.io/github/license/joelle-jnbaptiste/SchoolProject---Credit-scoring-model?style=for-the-badge" />
  <img src="https://img.shields.io/badge/School%20Project-ML%20%26%20Data-blueviolet?style=for-the-badge" />
</p>

<h1 align="center">✨ Credit Scoring Model ✨</h1>

<div align="center">
  <em>
     *Making financial risk understandable through interpretable data*
  </em>
</br>

 <b>End-to-end data preparation and exploratory analysis for a credit scoring use case, with a strong focus on interpretability</b>
</br>
</br>
🗃️ **Dataset**  
 https://www.kaggle.com/competitions/home-credit-default-risk
  
</div>

---


<!-- TABLE OF CONTENTS -->
<details>
  <summary>🧭 Table of Contents</summary>
  <ol>
    <li><a href="#-built-with">Built With</a></li>
    <li><a href="#-about-the-project">About The Project</a></li>
    <li><a href="#-dataset">Dataset</a></li>
    <li><a href="#-analysis-workflow">Analysis Workflow</a></li>
    <li><a href="#-repository-structure">Repository Structure</a></li>
    <li><a href="#-getting-started">Getting Started</a></li>
    <li><a href="#-license">License</a></li>
    <li><a href="#-contact">Contact</a></li>
  </ol>
</details>

---
### ✨ Built With

[![Python][Python-shield]][Python-url]
[![Jupyter][Jupyter-shield]][Jupyter-url]
[![Pandas][Pandas-shield]][Pandas-url]
[![NumPy][NumPy-shield]][NumPy-url]
[![Matplotlib][Matplotlib-shield]][Matplotlib-url]
[![Seaborn][Seaborn-shield]][Seaborn-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🎯 About The Project

This project explores a **credit scoring use case** in a financial context.

You are acting as a **Data Scientist** in a consumer credit company whose objective is to:

- Estimate the probability that a client will repay a loan
- Classify loan applications as approved or rejected
- Provide a model that is **interpretable** for business users and decision-makers

This repository focuses on the **data preparation and exploratory analysis phase**, which includes:

- Data cleaning and missing value handling
- Univariate and multivariate analysis
- Feature engineering
- Correlation analysis
- Preparation of a clean dataset ready for modeling

The work is performed entirely in **Jupyter Notebooks**, with a strong emphasis on **readability**, **methodology**, and **explainability**.

---

## 🗃️  Dataset

The dataset comes from a public Kaggle competition commonly used as a benchmark for credit scoring problems.

Source:  
https://www.kaggle.com/competitions/home-credit-default-risk

The dataset includes:

- Historical loan information
- Client demographic and financial attributes
- Behavioral indicators
- A binary target indicating loan default

The dataset is adapted and reused here for **educational and professional training purposes**.

---

## 🧠 Analysis Workflow

The notebook follows a structured and realistic workflow:

1. **Business Understanding**
   - Credit risk context
   - Target definition
   - Interpretability constraints

2. **Exploratory Data Analysis (EDA)**
   - Target distribution
   - Feature distributions
   - Missing value analysis

3. **Data Cleaning**
   - Removal of irrelevant features
   - Handling missing values
   - Encoding categorical variables

4. **Feature Engineering**
   - Creation of ratio-based features
   - Interaction features
   - Domain-driven transformations

5. **Correlation & Multivariate Analysis**
   - Correlation matrices
   - Redundancy detection
   - Feature importance intuition

6. **Dataset Export**
   - Cleaned dataset saved as CSV
   - Ready for modeling and experimentation

Several notebooks also explore **model explainability techniques** (LIME, feature importance) to illustrate how predictions can be interpreted.

---

## 🗺️ Repository Structure

    SchoolProject---Credit-scoring-model/
    ├── notebooks/
    │   ├── Jean_Baptiste_Joelle_1_notebook_analytique.ipynb
    │   ├── Jean_Baptiste_Joelle_2_notebook_modelisation.ipynb
    │   ├── lime_explanation_Dummy_Classifier.ipynb
    │   ├── lime_explanation_Gradient_Boosting.ipynb
    │   ├── lime_explanation_Logistic_Regression.ipynb
    │   ├── lime_explanation_Random_Forest.ipynb
    │   └── lime_explanation_SVM.ipynb
    └── README.md

---

## ⚔️ Getting Started

This project is designed to be explored locally using **Jupyter Notebook**.

### Prerequisites

- Python 3.9+
- pip or conda
- Jupyter Notebook or JupyterLab

### Installation

1. Clone the repository:

       git clone https://github.com/joelle-jnbaptiste/SchoolProject---Credit-scoring-model.git

2. Install dependencies:

       pip install -r requirements.txt

3. Launch Jupyter:

       jupyter notebook

4. Open the notebooks and follow the analysis step by step.

---

## ✒️ License

This project is provided for educational purposes.  
The dataset follows Kaggle’s terms of use.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## 🕊️ Contact

Joëlle JEAN BAPTISTE  
LinkedIn: https://fr.linkedin.com/in/joëllejnbaptiste  

Project Link: https://github.com/joelle-jnbaptiste/SchoolProject---Credit-scoring-model

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

[Python-shield]: https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white
[Python-url]: https://www.python.org/
[Jupyter-shield]: https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white
[Jupyter-url]: https://jupyter.org/
[Pandas-shield]: https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white
[Pandas-url]: https://pandas.pydata.org/
[NumPy-shield]: https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white
[NumPy-url]: https://numpy.org/
[Matplotlib-shield]: https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge
[Matplotlib-url]: https://matplotlib.org/
[Seaborn-shield]: https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge
[Seaborn-url]: https://seaborn.pydata.org/
