# League of Legends Match Predictor

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white)

An advanced machine learning project aimed at predicting the winning team in a League of Legends match based on in-game statistics. This repository provides a complete pipeline from data processing and feature engineering to model training and evaluation.

## 🚀 About This Project

The goal of this project is to explore various machine learning models to accurately predict match outcomes in League of Legends. By analyzing a dataset of ranked matches, we identify key features that contribute to a team's success and build a predictive model to forecast the winner.

## ✨ Key Features

* **Data Analysis & Visualization:** In-depth exploratory data analysis (EDA) to understand the dataset and feature correlations.
* **Feature Engineering:** Creation of meaningful features from raw match data to improve model performance.
* **Model Training:** Implementation and comparison of various classification models (e.g., Logistic Regression, Random Forest, Gradient Boosting).
* **Performance Evaluation:** Rigorous evaluation of models using metrics like accuracy, precision, recall, and F1-score.
* **Prediction Pipeline:** A clear and reusable pipeline to make predictions on new match data.

## 🛠️ Technology Stack

* **Python:** The core programming language used for the project.
* **Pandas:** For data manipulation and analysis.
* **NumPy:** For numerical operations.
* **Scikit-learn:** For implementing machine learning models and evaluation metrics.
* **Matplotlib & Seaborn:** For data visualization.
* **Jupyter Notebook:** For interactive development, analysis, and documentation.

## 📊 Dataset

This project utilizes the "League of Legends Diamond Ranked Games (10 min)" dataset, which can be found on Kaggle. It contains data for approximately 10,000 ranked games.

* **Link to Dataset:** [League of Legends Diamond Ranked Games on Kaggle](https://www.kaggle.com/datasets/bobbyscience/league-of-legends-diamond-ranked-games-10-min)

Each entry in the dataset represents the state of a single match after 10 minutes.

## ⚙️ Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You will need Python 3.x and pip installed on your machine.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/SID41214/League-of-Legends-Match-Predictor.git](https://github.com/SID41214/League-of-Legends-Match-Predictor.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd League-of-Legends-Match-Predictor
    ```
3.  **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

The main logic, analysis, and model training process are detailed in the Jupyter Notebook `lol_match_predictor.ipynb`.

To run the notebook:
```bash
jupyter notebook lol_match_predictor.ipynb
```
Inside the notebook, you can execute the cells sequentially to see the entire process, from data loading to making final predictions.

## 🤝 Contributing

Contributions make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project.
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the Branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.
