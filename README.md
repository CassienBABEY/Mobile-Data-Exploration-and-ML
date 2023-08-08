# Mobile-Data-Exploration-and-ML

This repository contains datasets, data cleaning, data visualization, and machine learning models for predicting mobile phone prices based on text data.

## Datasets

The datasets used in this project are stored in the `data` folder. There are three datasets available:
- `mobile.csv`: The original dataset containing mobile phone recommendations. [data_source](https://www.kaggle.com/datasets/gyanprakashkushwaha/mobile-recommendation-system-dataset)
- `mobile_characteristics.csv`: A new dataframe created using regex extraction from the `mobile.csv` dataset.
- `mobile_characteristics_processed.csv`: The cleaned version of the `mobile_characteristics.csv` dataset after exploratory data analysis.

## Notebooks

### 1. Lets-Make-a-New-Dataframe-Regex-Extraction.ipynb

In this notebook, we create a new dataframe (`mobile_characteristics.csv`) using regular expression extraction techniques. We extract information from the name and corpus of mobile phones to create a more informative dataset.

### 2. Exploratory Data Analysis on mobile characteristics.ipynb

This notebook focuses on exploratory data analysis (EDA) of the `mobile_characteristics.csv` dataset. We perform data visualization, handle missing values, and clean the dataset for further analysis.

### 3. Machine-Learning-Price-Prediction-of-a-Phone.ipynb

In this notebook, we build a machine learning pipeline for predicting the price of a mobile phone. We compare and optimize different machine learning models for price prediction, considering features extracted from the text data.

## How to Use

1. Clone this repository to your local machine.
2. Ensure you have the required libraries installed by running: `pip install -r requirements.txt`
3. Run the notebooks in the order mentioned above to replicate the data preprocessing, exploratory analysis, and machine learning process.
4. Feel free to modify the notebooks, add your own analysis, or experiment with different models.

## Credits

This project was developed by [Cassien BABEY].

Happy exploring and modeling!
