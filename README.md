# PRODIGY_DS_02
# Titanic Dataset Analysis

This project involves performing data cleaning and exploratory data analysis (EDA) on the Titanic dataset from Kaggle. The goal is to explore the relationship between variables and identify patterns and trends in the data.

## Dataset

The dataset can be found [here](https://www.kaggle.com/c/titanic).

## Setup

### Prerequisites

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Kaggle API

### Installing Dependencies

To install the necessary dependencies, run:

pip install pandas numpy matplotlib seaborn kaggle

### Configuring the Kaggle API
Go to your Kaggle account and create a new API token. This will download the kaggle.json file.

Move the kaggle.json file to the appropriate location:

Windows: C:\Users\<Your-Username>\.kaggle\

### Download dataset and run script

-Run the following command to download the dataset:

kaggle competitions download -c titanic

-The analysis is performed in the Jupyter notebook Task2.ipynb. To start the Jupyter notebook, run:    

jupyter notebook titanic_analysis.ipynb

### Project Structure    
1.Task2.ipynb: Jupyter notebook containing the data cleaning and EDA.  
2.train.csv: Training dataset.  
3.test.csv: Test dataset.  

### The exploratory data analysis (EDA) includes:  
1.Handling missing values  
2.Analyzing the distribution of variables  
3.Exploring relationships between variables  
4.Identifying patterns and trends  
### Conclusion  
This analysis provides insights into the factors that might have influenced the survival of passengers on the Titanic. The knowledge gained can be further used to build predictive models.
