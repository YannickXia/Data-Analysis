Car Sales Data Analysis

Introduction

This project is an Exploratory Data Analysis (EDA) of the Car Sales Dataset – Model, Features, and Pricing, a mock dataset of second-hand car sales from Kaggle. The goal of this project is to visualize and understand how different features such as brand, fuel type, year of manufacture, engine size, and mileage affect car prices.

Dataset
	•	Source: Kaggle – Car Sales Dataset: Model, Features, and Pricing
	•	Size: 50,000 rows
	•	Main columns:
	•	Manufacturer
	•	Model
	•	Engine size
	•	Fuel type
	•	Year of manufacture
	•	Mileage
	•	Price

Analysis Performed

The following visualizations were created to explore the dataset:
	•	Price Distribution
	•	Year of Manufacture Distribution
	•	Fuel Type Count
	•	Mileage vs Price (scatter plot)
	•	Engine Size vs Price (scatter plot)
	•	Fuel Type vs Price (box plot)
	•	Top 10 Car Brand Distribution (pie chart)

Key Findings
	•	The dataset is dominated by Ford, VW, and Toyota, which together account for more than 80% of the cars.
	•	Car prices are right-skewed, with most vehicles falling in the low-to-mid price range.
	•	Car age and mileage are negatively correlated with price: newer cars with lower mileage are typically more expensive.
	•	Fuel type also influences pricing: hybrids tend to have higher prices in certain cases compared to petrol and diesel cars.

Usage
	1.	Clone this repository or download the files.
	2.	Open the Car_Sales_EDA.ipynb notebook in Jupyter Notebook or JupyterLab.
	3.	Run the notebook cells sequentially to reproduce the visualizations.

Conclusion

This is an entry-level data analysis project focusing on data visualization and basic insights. Although no predictive modeling has been implemented yet, the analysis provides a clear overview of how different features affect car prices and sets the foundation for potential future work such as price prediction models or dashboard applications.
