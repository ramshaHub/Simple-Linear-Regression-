**Introduction**
This project demonstrates a Simple Linear Regression model that predicts the tips given in restaurants based on the total bill amount. Using Python, the model is built using the scikit-learn library. The dataset contains two main features: total_bill (independent variable) and tip (dependent variable).

**Project Structure**
Dataset: A dictionary is provided containing the total bill and tip amounts.
Model: Linear regression model is created using LinearRegression from scikit-learn.
Evaluation: The model is evaluated using Mean Squared Error (MSE) and R-squared (R²) metrics.
Visualization: Scatter plots are used to visualize the relationship between the total bill and the tip, as well as the actual vs predicted values.

**Prerequisites**
To run this project, you need the following Python libraries:
pandas
numpy
matplotlib
scikit-learn
You can install these libraries using the following commands:
pip install pandas numpy matplotlib scikit-learn

**How the Project Works**
Dataset: The dataset contains two columns, total_bill and tip, representing the total bill amounts and the corresponding tips.
Data Visualization: A scatter plot is created to show the relationship between the total bill and the tip amounts.
Data Splitting: The data is split into training and testing sets using an 80-20 split.
Model Creation: A linear regression model is trained on the training set.
Predictions: The model makes predictions on the test set.
Evaluation: The model is evaluated using the Mean Squared Error and R-squared metrics.
Comparison of Actual and Predicted Values: The actual vs predicted values are compared in a tabular format and visualized with a scatter plot.

**Code Explanation**
Dataset Creation: The dataset is created using a dictionary and converted into a pandas DataFrame.
Scatter Plot: The relationship between total bill and tip is visualized using matplotlib.
Data Splitting: The data is split into training and testing sets using train_test_split from sklearn.
Model Training: The LinearRegression model is trained on the training data.
Prediction: The model makes predictions on the test data.
Model Evaluation: The performance of the model is evaluated using MSE and R².
Result Comparison: A comparison table of actual vs predicted values is printed.
Visualization: The test set and regression line are visualized in a scatter plot.

**Running the Project**
To run the project:
Clone the repository or download the code file.
Ensure that the required Python packages are installed.

**Run the Python script in bash**
python simple_linear_regression.py

**Output**
The project outputs:
A scatter plot showing the relationship between total_bill and tip.
MSE and R² values printed on the console.
A table comparing actual vs predicted values.
A plot showing actual vs predicted values with a regression line.

**License**
This project is open-source and free to use under the MIT License.
