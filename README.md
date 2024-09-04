---

# SPE DSEAT Datathon 2024 - Oil, Gas, and Water Production Prediction

## Project Overview

This repository contains the code and resources developed for the 2024 SPE DSEAT D Datathon. The primary objective of this project was to build a machine learning model capable of predicting oil, gas, and water production based on historical production records. This project aimed to enhance predictive accuracy in the oil and gas industry, providing valuable insights to optimize operations and decision-making.

## Project Structure

The repository is organized as follows:

- **data/**: Contains the historical production data used for training and testing the models.
- **notebooks/**: Jupyter notebooks with the data exploration,data preprocessing, training, and evaluation, feature engineering, and model development processes.
- **models/**: Saved machine learning models and related files.
- **results/**: Output files, including model performance metrics and visualizations.

## Approach

1. **Data Exploration**:
   - Conducted an initial exploration of the historical data to understand the distributions and identify any data quality issues.
   - Visualized trends in oil, gas, and water production over time.

2. **Feature Engineering**:
   - Created features based on temporal aspects, such as month, season, and year.
   - Engineered features to capture production trends and potential correlations between different production types.

3. **Model Development**:
   - Developed several machine learning models, including Linear Regression, Random Forest, and Gradient Boosting, to predict production values.
   - Hyperparameter tuning was performed to optimize model performance.

4. **Model Evaluation**:
   - Evaluated the models using standard metrics like RMSE, MAE, and R².
   - Selected the best-performing model based on cross-validation results and tested it on unseen data.

5. **Results**:
   - The final model showed strong predictive capabilities, with an RMSE of X and R² of Y on the test dataset.
   - Visualizations of the predictions vs. actual values are available in the `results/` directory.

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/spe-dseat-datathon-2024.git
   ```

2. **Install Dependencies**:
   Make sure you have Python 3.x installed. Install the required packages using pip:
   ```bash
   pip install python 3
   ```

3. **Run the Notebooks**:
   Navigate to the `notebooks/` directory and open the Jupyter notebooks to explore the data, train the models, and evaluate the results.

4. **Reproduce the Results**:
   Run the scripts in the `scripts/` directory to preprocess the data, train the model, and generate predictions.

## Future Work

- **Model Improvement**: Experiment with more advanced machine learning algorithms and deep learning models to improve predictive accuracy.
- **Feature Engineering**: Explore additional features that may contribute to model performance, such as geological data or market trends.
- **Deployment**: Develop a pipeline to deploy the model for real-time prediction in a production environment.

## Acknowledgments

This project was developed as part of the 2024 SPE DSEAT D Datathon. Special thanks to the competition organizers and mentors for their guidance and support.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
