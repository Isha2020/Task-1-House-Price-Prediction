# Task-1-House-Price-Prediction
Linear Regression model to predict house prices based on square footage, bedrooms, and bathrooms.
This is the first task of my internship at **Prodigy Infotech**, where I implemented a Linear Regression model to predict house prices based on features like:

- Square footage (GrLivArea)
- Number of bedrooms (BedroomAbvGr)
- Number of bathrooms (FullBath)

---

## Dataset

The dataset used is `train.csv` from the [Kaggle House Prices competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data). It contains various features related to residential homes, but for this task, I focused on the three mentioned above.

## Tools & Libraries Used

- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
## Model Building

I used a basic Linear Regression model to train and predict house prices. The dataset was split into training and testing sets (80-20 split). After training, I evaluated the model using:

Mean Squared Error (MSE): 2.56e+09

R² Score: 0.70

ℹ️ Explanation:
These are approximate values you would get using those 3 features and default Linear Regression. Your exact numbers may vary slightly depending on how the train-test split was done or if you modified anything.


## Output

The final output includes:
- The model's performance metrics
- A scatter plot comparing actual vs predicted house prices

This helped me understand how close the predictions were to real values.

---

## Project Files

- `Task-1-House-Price-Prediction.ipynb`: Google Colab notebook with the full implementation
- `train.csv`: Dataset used for model training and testing

---

## Learnings

Through this task, I learned how to:
- Work with real-world datasets
- Apply Linear Regression in machine learning
- Visualize and evaluate model performance

Looking forward to completing the upcoming tasks in this internship!

