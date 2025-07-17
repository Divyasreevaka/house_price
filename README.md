🏡 House Price Prediction

Project Overview

In this task , our goal is to use data from the California census to create a machine learning model to predict house prices in the state.

Ultimately, our machine learning model should learn from this data and be able to predict the median house price in any neighborhood, given all other relevant metrics.

Dataset

The dataset consists of housing-related attributes collected from the California census. It contains various features that influence house prices, including:

- Longitude & Latitude – Geographical location of the district.

- Housing Median Age – The age of houses in the district.

- Total Rooms – Total number of rooms in a district.

- Total Bedrooms – Total number of bedrooms in a district.

- Population – Total population in the district.

- Households – Number of households in a district.

- Median Income – Average income of households.

- Median House Value – Target variable representing house prices.

- Ocean Proximity – Proximity of the district to the ocean.

This dataset will serve as the foundation for training and testing our machine learning model.

Machine Learning Models Used

✅ Linear Regression – A simple yet effective model for establishing relationships between features and house prices.

Evaluation Metrics

To assess model performance, the following metrics were used:

RMSE (Root Mean Square Error) – Measures prediction error

MAE (Mean Absolute Error) – Average absolute error

MSE (Mean Squared Error) – Squared difference between predicted & actual values

R² (Coefficient of Determination) – Model's predictive power

🛠 Installation & Usage

🔹 Clone the Repository

git clone https://github.com/Divyasreevaka/house_price.git cd house_price

🔹 Install Dependencies

pip install -r requirements.txt

🔹 Run the Jupyter Notebook

jupyter notebook house_price.ipynb

Follow the notebook to explore data, preprocess it, train models, and evaluate results.

License

This project is open-source under the MIT License.

Contributions

Contributions are welcome! Feel free to open an issue or submit a pull request to improve the project. 
