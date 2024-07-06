# XGBoost Home Price Prediction

This project uses XGBoost to predict home prices based on various features of the houses. XGBoost is a powerful and efficient implementation of gradient boosting for supervised learning. The project was developed using Jupyter Notebook (.ipynb) files for an interactive and exploratory approach.

## Features

- **Data Preprocessing**: Handling missing values, feature engineering, and scaling.
- **Model Training**: Using XGBoost to train the model on the processed data.
- **Model Evaluation**: Evaluating the model performance using metrics like RMSE (Root Mean Squared Error).
- **Prediction**: Making predictions on new data.
- **Data Visualization**: Utilizing matplotlib and seaborn for visualizing data distributions and relationships.

## Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/XGBoost-Home-Price-Prediction.git
    ```
2. **Navigate to the project directory:**
    ```sh
    cd XGBoost-Home-Price-Prediction
    ```
3. **Install the required dependencies:**
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. **Start Jupyter Notebook:**
    ```sh
    jupyter notebook
    ```
2. **Open the notebook and run the cells in order:**
    - `housesalesprediction.ipynb`: This notebook contains all the steps for data preprocessing, model training, evaluation, and prediction.

## Project Structure

- `housesalesprediction.ipynb`: Jupyter Notebook containing the complete workflow for data preprocessing, model training, evaluation, and prediction.
- `kc_house_data.csv`: Dataset containing the house features and prices.
- `requirements.txt`: List of required dependencies.

## Data

The dataset used for this project is `kc_house_data.csv`. Ensure the data is properly cleaned and formatted before running the notebook.

## Model

The XGBoost model is used for predicting home prices. XGBoost is known for its efficiency and performance, making it a suitable choice for this regression task.

## Evaluation

The model is evaluated using RMSE (Root Mean Squared Error), which measures the average magnitude of the errors between predicted and actual values.

## Libraries Used

- **numpy**: For numerical operations.
- **pandas**: For data manipulation and analysis.
- **matplotlib**: For data visualization.
- **seaborn**: For statistical data visualization.
- **mpl_toolkits**: For advanced plotting.
- **XGBoost**: For the machine learning model.

## Contributing

Feel free to fork the repository and submit pull requests. Any contributions are welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
