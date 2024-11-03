# House Price Analysis and Prediction

This project aims to analyze and predict house prices using a dataset of housing data from California. We employ **Regression**, **Classification**, and **Clustering** models to explore the relationships and patterns in the dataset.

## Dataset
The dataset (`housing.csv`) is in the `data/` folder and contains information such as:
- **Longitude and Latitude** of each property
- **Median income** and **House age**
- **Rooms per household**, **Population per household**, etc.
- **Ocean proximity** as a categorical feature.

## Project Structure
The project is organized as follows:
- `data/`: Contains the dataset (`housing.csv`).
- `notebooks/cali_housing_prices_prediction.ipynb`: Includes three parts:
  - `regression_analysis`: For predicting house prices using regression models.
  - `classification_analysis`: For classifying properties as above or below median price.
  - `clustering_analysis`: For grouping similar properties using clustering.
- `results/`: Stores model evaluation metrics (`results_summary.txt`) and clustering analysis visuals (`elbow_silhouette.png`).
- `requirements.txt`: Lists dependencies required to run the notebooks.

## Installation
To run this project, clone the repository and install dependencies with:
```bash
pip install -r requirements.txt
