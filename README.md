<!-- Improved compatibility of back to top link -->
<a id="readme-top"></a>

<!-- PROJECT SHIELDS -->
[![Stars][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">

<h3 align="center">🪄 Credit Scoring Model</h3>

<p align="center">
  End-to-end data preparation and exploratory analysis for a credit scoring model, focusing on data cleaning, feature engineering, and interpretability in a financial context.
  <br />
  <br />
  <a href="https://www.kaggle.com/code/willkoehrsen/start-here-a-gentle-introduction"><strong>View Data Source »</strong></a>
  <br />
  <br />
  <a href="https://github.com/joelle-jnbaptiste/SchoolProject---Public-health-data-preparation">Repository</a>
</p>
</div>

---

<!-- TABLE OF CONTENTS -->
<details>
  <summary>📜 Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">🔮 About The Project</a>
      <ul>
        <li><a href="#data-source">🧪 Data Source</a></li>
        <li><a href="#built-with">✨ Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">🪄 Getting Started</a>
      <ul>
        <li><a href="#prerequisites">📘 Prerequisites</a></li>
        <li><a href="#installation">🧙 Installation</a></li>
      </ul>
    </li>
    <li><a href="#analysis-workflow">📖 Analysis Workflow</a></li>
    <li><a href="#roadmap">🗺️ Roadmap</a></li>
    <li><a href="#license">📄 License</a></li>
    <li><a href="#contact">📬 Contact</a></li>
  </ol>
</details>

---

## 🔮 About The Project

This project is part of a **credit scoring use case** in a financial context.

You are acting as a **Data Scientist** in a consumer credit company whose goal is to:
- Estimate the probability that a client will **repay a loan**
- Classify loan applications as **approved or rejected**
- Provide a **model that is interpretable** for business users (customer relationship teams)

This repository focuses on the **data preparation and exploratory analysis phase**, which includes:
- Data cleaning and missing value handling
- Univariate and multivariate analysis
- Feature engineering
- Correlation analysis
- Export of a cleaned dataset ready for modeling

The work is performed entirely in **Jupyter Notebook** with a strong emphasis on **readability and interpretability**.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

### 🧪 Data Source

The dataset comes from a public Kaggle competition and is commonly used as a benchmark for credit scoring problems.

- Source:  
  https://www.kaggle.com/code/willkoehrsen/start-here-a-gentle-introduction

The data contains:
- Historical loan information
- Client demographic and financial attributes
- Behavioral indicators
- A binary target indicating loan default

This project reuses and adapts the kernel to fit a **professional and pedagogical context**.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

### ✨ Built With

[![Python][Python-shield]][Python-url]
[![Jupyter][Jupyter-shield]][Jupyter-url]
[![Pandas][Pandas-shield]][Pandas-url]
[![NumPy][NumPy-shield]][NumPy-url]
[![Matplotlib][Matplotlib-shield]][Matplotlib-url]
[![Seaborn][Seaborn-shield]][Seaborn-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## 🪄 Getting Started

This project is designed to be explored locally using **Jupyter Notebook**.

### 📘 Prerequisites

- Python 3.9+
- pip or conda
- Jupyter Notebook or JupyterLab

### 🧙 Installation

1. Clone the repository:

       git clone https://github.com/joelle-jnbaptiste/SchoolProject---Public-health-data-preparation.git

2. Install dependencies:

       pip install -r requirements.txt

3. Launch Jupyter:

       jupyter notebook

4. Open the notebook and follow the analysis step by step.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## 📖 Analysis Workflow

The notebook follows a structured workflow:

1. **Business understanding**
   - Credit risk context
   - Target definition
   - Interpretability constraints

2. **Exploratory Data Analysis (EDA)**
   - Target distribution
   - Feature distributions
   - Missing values analysis

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
   - Feature importance intuition
   - Redundancy detection

6. **Dataset Export**
   - Cleaned dataset saved as CSV
   - Ready for modeling and experimentation

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## 🗺️ Roadmap

- [ ] Add baseline machine learning model
- [ ] Compare multiple classification algorithms
- [ ] Add global feature importance analysis
- [ ] Add local explainability for individual predictions
- [ ] Integrate SHAP or similar interpretability tools

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## 📄 License

This project is provided for **educational purposes**.  
The dataset follows Kaggle’s terms of use.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## 📬 Contact

Joëlle JEAN BAPTISTE  
LinkedIn: https://fr.linkedin.com/in/joëllejnbaptiste  

Project Link:  
https://github.com/joelle-jnbaptiste/SchoolProject---Public-health-data-preparation

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

<!-- MARKDOWN LINKS & IMAGES -->
[stars-shield]: https://img.shields.io/github/stars/joelle-jnbaptiste/SchoolProject---Public-health-data-preparation.svg?style=for-the-badge
[stars-url]: https://github.com/joelle-jnbaptiste/SchoolProject---Public-health-data-preparation/stargazers
[issues-shield]: https://img.shields.io/github/issues/joelle-jnbaptiste/SchoolProject---Public-health-data-preparation.svg?style=for-the-badge
[issues-url]: https://github.com/joelle-jnbaptiste/SchoolProject---Public-health-data-preparation/issues
[license-shield]: https://img.shields.io/badge/License-Educational-purple?style=for-the-badge
[license-url]: #
[linkedin-shield]: https://img.shields.io/badge/LinkedIn-4B0082?style=for-the-badge&logo=linkedin&logoColor=white
[linkedin-url]: https://fr.linkedin.com/in/joëllejnbaptiste

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
