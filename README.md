# Used Cars Price Prediction

This project predicts the prices of used cars using Linear Regression in Python. The model achieves approximately 80% accuracy, evaluated using the Root Mean Square Error (RMSE) method.

## Features
- Predicts selling prices of used cars based on features like Year, Mileage, Fuel Type, Transmission, Engine, Power, and Owner Type.
- Utilizes Linear Regression to establish relationships between features and the target variable (Price).
- Achieves around 80% accuracy as evaluated by RMSE.

## Dataset
The dataset includes the following columns:
- **Year**: Manufacturing year of the car
- **Mileage**: Distance traveled by the car
- **Fuel Type**: Type of fuel (Petrol, Diesel, CNG, etc.)
- **Transmission**: Manual or Automatic
- **Owner Type**: Number of previous owners
- **Engine**: Engine capacity
- **Power**: Engine power
- **Price**: Selling price of the car (Target Variable)

## Technologies Used
- **NumPy**: Numerical operations and array manipulation
- **Pandas**: Data manipulation and analysis
- **Matplotlib & Seaborn**: Data visualization
- **Scikit-learn**: Linear Regression model building and evaluation
- **Joblib**: Model saving and loading

## Model Evaluation
- The model is evaluated using the Root Mean Square Error (RMSE) method.
- Achieves approximately 80% accuracy.

## Installation
1. Clone the repository:
    ```
    git clone https://github.com/your-username/used-cars-price-prediction.git
    ```
2. Install the required libraries:
    ```
    pip install numpy pandas scikit-learn matplotlib seaborn joblib
    ```

## Usage
- Run the Jupyter Notebook to load the dataset, preprocess data, train the model, and evaluate its performance.
- Use the saved model to predict prices on new data.

## License
This project is licensed under the MIT License.
