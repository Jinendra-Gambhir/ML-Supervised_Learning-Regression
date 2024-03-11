
# Boston House Price Prediction

This project focuses on predicting house prices in Boston using a machine learning model. The dataset used for this project is sourced from Kaggle ([Boston House Prices Dataset](https://www.kaggle.com/datasets/vikrishnan/boston-house-prices)). The implementation includes data exploration, preprocessing, model training using the XGBoost regressor, and evaluation metrics.



## Acknowledgements

 - Special thanks to the dataset provider and the Kaggle community for making this project possible.

## Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Heatmap | ![#0000ff](https://via.placeholder.com/10/0a192f?text=+) #0000ff |
| Scatter Plot | ![#0000ff](https://via.placeholder.com/10/00b48a?text=+) #0000ff |

- Blue: Used in the heatmap for data correlation.
- Blue: Used in the scatter plot for actual vs predicted price.
## Features

- House price prediction
- Correlation analysis
- Heatmap visualization


## Screenshots

![](https://github.com/Jinendra-Gambhir/ML-Supervised_Learning-Regression/blob/main/heatmap.png)


## Tech Stack

- Python
- XGBoost
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
## Usage/Examples
## Example 1: Loading and Exploring the Dataset

```Python
# Loading the dataset in pandas Data Frame
house_price_dataset = pd.read_csv("/content/housing.csv")
house_price_dataset.rename(columns={"medv":"price"}, inplace=True)

# Checking shape of DataFrame
print(house_price_dataset.shape)

# Checking missing Values
print(house_price_dataset.isnull().sum())
```
## Example 2: Correlation Heatmap Visualization
```Python
# Constructing heatmap to understand correlation
plt.figure(figsize=(10,10))
sns.heatmap(correlation, cbar=True, square=True, fmt=".1f", annot=True, annot_kws={"size":8}, cmap="Blues")
```


## Authors

- [@Jinendra Gambhir](https://www.github.com/Jinendra-Gambhir)


## Feedback

Feedback is welcome! Feel free to open an issue for suggestions or bug reports.


## 🔗 Links
[![GitHub](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](github.com/Jinendra-Gambhir/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jinendragambhir/)
