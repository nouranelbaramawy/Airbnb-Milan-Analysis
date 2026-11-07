# Airbnb Milan Data Analysis

## About the Project

This project focuses on analyzing Airbnb listings in Milan, Italy. The goal is to explore the dataset, understand pricing patterns, compare different room types and neighbourhoods, and identify groups of listings with similar characteristics.

## Dataset

The dataset contains information about Airbnb listings, including:

- Price
- Room type
- Neighbourhood
- Minimum nights
- Number of reviews
- Availability
- Host information

## Data Cleaning

The following steps were performed:

- Checked missing values.
- Removed records with missing prices.
- Checked minimum nights for invalid values.
- Identified price outliers.
- Prepared the data for analysis.

Dataset information:
- Original rows: 25,338
- Cleaned rows: 21,654
- Price outliers: 1,568
- Rows used for price analysis: 20,086

## Analysis

The project includes:

- Basic statistics and data exploration.
- Price distribution analysis.
- Price comparison between room types.
- Analysis of the most and least expensive neighbourhoods.
- Correlation analysis between numerical features.
- Data visualization using different charts.

## K-Means Clustering

K-Means was used to group Airbnb listings based on price and minimum nights.

The data was standardized using StandardScaler, and the model was set to identify three clusters.

| Cluster | Listings | Average Price | Average Minimum Nights |
|---|---:|---:|---:|
| 0 | 12,611 | €141.27 | 1.53 |
| 1 | 5,150 | €273.41 | 2.27 |
| 2 | 2,195 | €97.81 | 34.81 |

## Tools Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## How to Run

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Open the Jupyter Notebook and run the cells in order.

Make sure the dataset is available in the correct folder.

## Conclusion

The analysis provides an overview of Airbnb listings in Milan, showing differences in prices, room types, and neighbourhoods. The clustering results also show how listings can be grouped according to their prices and minimum booking requirements.
