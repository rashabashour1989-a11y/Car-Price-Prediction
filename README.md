# Car Price Prediction Model 🚗💰

This project utilizes Machine Learning to predict the resale price of used cars based on various features such as brand, year of manufacture, mileage, fuel type, and more.

## 📊 Model Performance
The final model was developed using the **Gradient Boosting Regressor** algorithm, achieving an impressive accuracy:
* **R2 Score: 82.53%**

## 🛠️ Project Structure
The repository contains the following essential files:
1.  **`CarPriceModel.ipynb`**: The full Jupyter Notebook containing data cleaning, exploratory data analysis (EDA), and model training.
2.  **`CAR DETAILS FROM CAR DEKHO.csv`**: The dataset used for training and testing.
3.  **`car_price_model.pkl`**: The serialized (saved) trained model, ready for instant predictions.
4.  **`label_encoder.pkl`**: The saved LabelEncoder to handle categorical brand data.
5.  **`requirements.txt`**: List of Python libraries required to run this project.

## 🚀 How to Use
1.  Clone the repository.
2.  Install dependencies: `pip install -r requirements.txt`.
3.  Load the model using `joblib` and provide car details to get a price estimate.
## 🔑 Key Features Predicted
- **Brand**: The manufacturer of the car.
- **Vehicle Age**: Calculated from the year of manufacture.
- **Kilometers Driven**: Total distance covered.
- **Fuel Type**: Petrol, Diesel, etc.
- **Transmission**: Manual or Automatic.
- **Owner Type**: First owner, Second owner, etc.

---
*Created as part of a Data Science Portfolio.*
