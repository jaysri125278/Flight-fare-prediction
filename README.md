
# Flight Price Prediction

## Project Overview
This project involves predicting flight prices based on various factors such as the airline, journey date, source and destination, duration, and other related information. The aim is to build a machine learning model that can accurately forecast flight fares given these inputs.

## Dataset
The dataset used in this project is provided in an Excel file (`Data_Train.xlsx`) and includes the following columns:
- `Airline`: The name of the airline.
- `Date_of_Journey`: The date of the flight journey.
- `Source`: The source location from where the flight departs.
- `Destination`: The destination location where the flight arrives.
- `Route`: The route taken by the flight.
- `Dep_Time`: The departure time of the flight.
- `Arrival_Time`: The arrival time of the flight.
- `Duration`: The duration of the flight.
- `Total_Stops`: The total number of stops between source and destination.
- `Additional_Info`: Any additional information about the flight.
- `Price`: The target variable, representing the price of the flight.

## Project Steps
1. **Data Loading**: The dataset is loaded using `pandas.read_excel()` for analysis.
2. **Data Preprocessing**: 
   - Handling missing values: Any rows with missing data are removed using `dropna()`.
   - Data exploration: Initial exploration of the dataset to understand data types and the presence of null values.
   - Feature extraction: Columns like `Date_of_Journey` and `Duration` are further processed to extract relevant features for model training.
3. **Data Visualization**: Various plots are created using `matplotlib` and `seaborn` to visualize the data and understand the relationships between different features and the target variable.
4. **Model Training**: Machine learning models are trained on the processed data to predict flight prices.

## Libraries Used
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`

## How to Run the Project
1. Ensure that the necessary libraries are installed using pip:
   ```bash
   pip install numpy pandas matplotlib seaborn
   ```
2. Run the Jupyter Notebook (`flight_price.ipynb`) to see the data exploration, preprocessing, and model training steps.
3. Modify the notebook or use the provided code cells to experiment with different machine learning models.

## Conclusion
This project demonstrates a basic approach to predicting flight prices using a structured dataset. Through careful data preprocessing and exploration, a predictive model can be built to estimate the cost of flights based on various features.
