# Bank Marketing Prediction

## Overview
This project delves into the analysis of direct marketing campaigns conducted by a Portuguese banking institution. The main objective is to predict whether clients will subscribe to a term deposit based on various features collected during the campaigns. Through thorough analysis and machine learning techniques, we aim to provide insights into the factors influencing client decisions and optimize future marketing strategies.

## Dataset
The dataset consists of :


The dataset encompasses various features related to client demographics, previous campaign interactions, economic indicators, and social factors.

## Classification Goal
The primary classification goal is to predict whether a client will subscribe (`yes` or `no`) to a term deposit (variable `y`). This binary classification task involves employing machine learning algorithms to train predictive models based on historical campaign data.

## Conclusion
- **Predictive Performance**: Utilized cutting-edge machine learning methodologies, including **oversampling with SMOTE** and **hyperparameter tuning via GridsearchCV**, to develop a highly **accurate** predictive model. Achieved an impressive **89% accuracy** using the KNeighbours classifier.
- **Data Analysis**: Conducted comprehensive analysis of **complex** financial data to identify key predictors influencing client subscription decisions. This analysis involved exploring relationships between various features and the target variable, as well as detecting patterns and trends.
- **Strategic Insights**: Generated strategic insights to optimize future marketing efforts. These insights include identifying target demographics with a high propensity to subscribe to term deposits, refining communication strategies, and allocating resources effectively.

## Technologies Used
- **Python Libraries**: Leveraged Pandas for data manipulation, Scikit-learn for machine learning modeling, and Matplotlib along with Seaborn for data visualization.
- **Jupyter Notebooks**: Provided detailed analysis and implementation steps in Jupyter notebooks available in the `notebooks` directory.

## Getting Started
To get started with this project:

1. **Clone Repository**: Clone this repository to your local machine.
   ```
   git clone https://github.com/your-username/direct-marketing-analysis.git
   ```
2. **Download Dataset**: Download the dataset file `bank_full.csv`.
3. **Install Dependencies**: Install the required dependencies by running the following command:
   ```
   pip install -r requirements.txt
   ```
4. **Explore Notebooks**: Explore the Jupyter notebook provided in the repository to understand the data analysis and machine learning model implementation.

## License
This project is licensed under the [MIT License](LICENSE), allowing for modification and distribution under certain conditions.

---
