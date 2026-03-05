# IKEA Furniture Price Prediction Marc

A machine learning model that predicts IKEA furniture prices based on product attributes scraped from IKEA’s website.

This project explores how structured product data can be used to model pricing and identify which features most influence cost.

Built using data from the [IKEA Webscraper](https://github.com/gamladz/ikea-webscraper).

---

## Why this exists

Pricing is driven by multiple factors such as size, material, category, and design. This project investigates how well these factors can predict price using supervised learning.

The goals were to:

- Build a clean end-to-end machine learning pipeline  
- Compare different regression models  
- Understand which features drive pricing  
- Interpret model decisions in a meaningful way  

---

## Results

Tested models included:

- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  

Random Forest produced the strongest performance, capturing nonlinear relationships between features and price.

The project also includes statistical analysis to interpret feature importance and model behavior.

---

## Project Structure

The project is organized into four notebooks, each representing a stage in the pipeline:

### 1. Exploratory-Data-Analysis.ipynb
- Data cleaning and preprocessing  
- Feature engineering  
- Train/test split  

### 2. ML.ipynb
- Model training and comparison  
- Hyperparameter optimization using RandomizedSearchCV  

### 3. Interpretations.ipynb
- Model interpretation using statistical analysis  
- Feature importance and recursive feature elimination  
- Analysis of model behavior  

### 4. Interface.ipynb
- Simple input interface for generating predictions  

---

## How to run

Install dependencies:

```bash
pip install pandas numpy matplotlib scikit-learn statsmodels
