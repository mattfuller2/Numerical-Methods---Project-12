# Numerical-Methods---Project-12

# Rusty Bargain Used Car Price Prediction

### Description
This project involves building a machine learning model to predict the market value of used cars for the Rusty Bargain used car sales service. The company aims to develop an app that allows customers to quickly estimate the value of their vehicles based on historical data, including technical specifications, trim versions, and prices.

### Project Structure
- **notebook.ipynb**: Contains the data preparation, model training, and evaluation steps.
- **/datasets/**: Contains the historical car data used for model training and testing.
- **/output/**: Contains outputs such as model predictions and evaluation metrics.

### Objectives
The main objectives of the project are:
1. **Data Preparation**:
   - Load and clean the historical car data.
   - Perform feature engineering and scaling where necessary.
   
2. **Model Training**:
   - Train machine learning models to predict the market value of used cars.
   - Evaluate models based on prediction quality, speed, and training time.

3. **Model Evaluation**:
   - Compare models using metrics such as RMSE, prediction speed, and training time.
   - Optimize the model to meet Rusty Bargain's requirements for speed and quality.

### Findings
- **Prediction Quality**: The model was able to predict the market value of used cars with reasonable accuracy after feature scaling and model optimization.
- **Training Time**: The training time of the model was optimized to balance between performance and speed.
- **Prediction Speed**: The final model delivers quick predictions, making it suitable for real-time usage in Rusty Bargain's app.

### Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/rusty-bargain-car-price-prediction.git
2. Install the required dependencies
   pip install -r requirements.txt
3. Launch Jupyter Notebook
   jupyter notebook
