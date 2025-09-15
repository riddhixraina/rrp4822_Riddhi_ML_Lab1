# Machine Learning Lab 1: Ames Housing Price Prediction

> This assignment serves as an introductory lab to fundamental machine learning concepts using the popular Ames Housing dataset. The primary goal is to predict house sale prices based on various home attributes. The lab covers data loading, exploratory analysis, and a deep dive into simple linear regression by implementing models from scratch and comparing the impact of different loss functions.

---

## 📊 Dataset

-   **Source:** [Ames, Iowa Housing Data](https://www.chrismusco.com/machinelearning2024_grad/AmesHousing.csv)
-   **Target Variable:** `SalePrice`
-   **Predictors Explored:** `Gr Liv Area`, `Lot Area`, `TotRms AbvGrd`, etc.

## 🧠 Key Concepts Covered

-   **Data Handling:** Loading, cleaning, and manipulation with `pandas`.
-   **Simple Linear Regression:** Implementing the analytical (closed-form) solution for optimal parameters.
-   **Brute-Force Optimization:** Developing a grid search algorithm to find approximate model parameters.
-   **Loss Functions:** Comparing the behavior of three different loss functions in the presence of outliers:
    -   Squared Loss (L2)
    -   Absolute Loss (L1)
    -   Max Loss (L-infinity)
-   **Model Comparison:** Visualizing and discussing how the choice of loss function affects the final regression model.

## 🚀 How to Run

1.  **Prerequisites:** Ensure you have Python 3 and the following libraries installed:
    ```bash
    pip install pandas numpy matplotlib
    ```

2.  **Execution:** Run the Jupyter Notebook or Python script to perform the analysis, generate the comparison plots, and view the discussion on model performance.

## ✨ Key Findings

> The analysis demonstrates that the choice of loss function significantly impacts a model's fit, especially when predictor variables contain outliers. The **L1 (Absolute Loss)** fit proved to be the most robust to extreme values, providing a better trend for the bulk of the data, whereas the **L2 (Squared Loss)** fit was easily skewed by these outliers.
