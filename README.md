# Food Ingredient Clustering

This project uses nutritional data to **cluster food ingredients based on their nutrients, vitamins, and minerals**.

## Dataset

The dataset contains **10,250 USDA food records** with nutritional information such as:

* Energy, protein, fat, carbohydrates, fiber, and sugar
* Calcium, iron, magnesium, phosphorus, potassium, and sodium
* Zinc, copper, manganese, selenium, and vitamin C

After preprocessing, **9,156 records** were used for clustering.

## Methods

The data was cleaned, transformed, normalized using `StandardScaler`, and additional nutritional features were created.

Several clustering methods were tested:

* **DBSCAN**
* **HDBSCAN**
* **K-Means**

K-Means produced the most interpretable overall clustering structure. The final approach resulted in **10 food clusters**, including:

* Standard Meats & Poultry
* Processed Snacks & Sweets
* Starchy Veggies & Soups
* Fibrous & Green Veggies
* Sugary Drinks, Juices & Alcohol
* Grains, Nuts & Seeds
* Dairy Liquids, Formulas & Creams
* Fortified Cereals & Carbs
* Seafood & Organ Meats
* Vitamin Outliers

## Technologies

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, UMAP, HDBSCAN.

## Goal

The goal is to explore whether nutritional characteristics can be used to identify meaningful groups of food ingredients through unsupervised machine learning.
