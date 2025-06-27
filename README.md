# Wine-Price-Prediction-ML

readme_content = """# Wine Price Prediction Project

## Project Description
This project aims to build a predictive model to estimate wine prices based on various characteristics. The goal is to identify the factors that significantly influence wine prices and develop a model that can provide reasonably accurate price predictions.

## Data
The project utilizes a dataset containing information about different wines, including attributes like score (points), price, state, region, variety, and winery. The initial data underwent cleaning to handle missing values.

## Project Steps

1.  **Data Cleaning:** Handled missing values by dropping rows with missing prices and imputing missing categorical values. Dropped irrelevant columns. Converted categorical features into numerical representations using Label Encoding.
2.  **Exploratory Data Analysis (EDA):** Examined descriptive statistics, visualized correlations between numerical features (score and price), and explored the distributions of key variables.
3.  **Modeling:** Split the data into training and testing sets. Trained multiple regression models including Linear Regression, Lasso, Ridge, Bayesian Ridge, Decision Tree Regressor, Linear SVR, KNeighbors Regressor, and Random Forest Regressor.
4.  **Model Evaluation:** Evaluated the performance of each model using R-squared and Mean Squared Error (MSE).

## Results

Several regression models were trained and evaluated. The R-squared values for the models were:
- Linear Regression: 0.288
- Lasso: 0.287
- Ridge: 0.288
- Bayesian Ridge: 0.288
- Decision Tree Regressor: 0.329
- Linear SVR: 0.029
- KNeighbors Regressor: 0.405
- Random Forest Regressor: 0.590

The **Random Forest Regressor** model achieved the highest R-squared value (0.590) and the lowest Mean Squared Error (275.005), indicating it performed the best among the evaluated models in capturing the variance in wine prices.

The visualizations of predicted vs actual prices for both KNeighbors Regressor and Random Forest Regressor showed that Random Forest handled outliers better and provided a closer fit to the actual values, further supporting its superior performance.

## How to Run the Code

1.  **Clone the repository:**
    ```bash
    git clone <https://github.com/Milind1505/Wine-Price-Prediction-ML/tree/main>
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd wine-price-prediction
    ```
3.  **Install necessary libraries:**
    Ensure you have Python installed. Install the required libraries using pip:
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn
    ```
4.  **Open and run the notebook:**
    The code is provided in a Jupyter Notebook format (`wine_price_prediction_notebook.ipynb`). You can open and run this notebook in environments like Google Colab or a local Jupyter environment (Jupyter Notebook or JupyterLab).
    *   **Google Colab:** Upload the notebook to Google Colab and run the cells sequentially. You may need to mount your Google Drive if the data file is stored there.
    *   **Local Jupyter Environment:** Start a Jupyter server in the project directory and open the notebook. Run the cells sequentially.

## Key Findings

*   The Random Forest Regressor model was the most effective model for predicting wine prices based on the dataset used.
*   While the Random Forest model showed the best performance with an R-squared of 0.590, there is still room for improvement, suggesting that other factors not included in this dataset might play a significant role in determining wine prices.
*   Exploratory analysis showed some correlation between score and price, and visualizations helped understand the data distribution and model predictions.
"""

print(readme_content)
