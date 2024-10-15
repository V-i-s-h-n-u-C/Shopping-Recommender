# Shopping Recommender System

## Overview

This project implements a shopping recommender system designed to enhance the user experience in e-commerce by providing personalized product recommendations. The system utilizes collaborative filtering, content-based filtering, and hybrid models to suggest products based on customer purchase history and browsing behavior. 

## Project Objectives

- Recommend products to customers based on their historical purchase data and browsing behavior.
- Enhance the customer shopping experience by providing personalized and relevant product suggestions.
- Increase customer engagement and satisfaction by accurately predicting products of interest.
- Leverage various recommendation techniques and evaluation metrics to deliver an optimal solution.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Features

- **Personalized Recommendations**: Suggests products based on user preferences and historical data.
- **Collaborative Filtering**: Utilizes user-item interactions to recommend products.
- **Content-Based Filtering**: Leverages product features and user profiles to generate recommendations.
- **Hybrid Model**: Combines collaborative and content-based techniques for improved accuracy.
- **Evaluation Metrics**: Measures performance using precision, recall, F1-score, and mean average precision.

## Installation Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/V-i-s-h-n-u-C/Shopping-Recommender.git

2. Navigate to the project directory:
   ```bash
   cd shopping-recommender

3. Install required packages:
   ```bash
   pip install -r requirements.txt

## Usage

1. Run the main script:
   ```bash
   Shopping Recommender System.py

2. The system will output the top 5 collaborative, content-based, and hybrid product recommendations for a specified user (e.g., user ID: 266783).

3. Evaluation metrics will also be displayed to assess the performance of the recommender system.

## Data

The dataset used for this project consists of three main CSV files:
- **Customer.csv**: Contains customer profiles including customer ID, date of birth, gender, and city code.
- **Transactions.csv**: Contains transaction records including transaction ID, product codes, quantity, rate, and total amount.
- **prod_cat_info.csv**: Contains product category and subcategory information.

## Output

The expected output includes:

- Top 5 collaborative product recommendations.
- Top 5 content-based product recommendations.
- Top 5 hybrid product recommendations.
- Evaluation metrics including precision, recall, and F1-score.

## Evaluation Metrics

The recommender system's performance is assessed using:

- Precision: Measures the accuracy of the recommendations.
- Recall: Indicates how many relevant items are recommended.
- F1-Score: Combines precision and recall for a balanced metric.

## Acknowledgments

- Scikit-learn for machine learning algorithms.
- Pandas for data manipulation.
- Matplotlib and Seaborn for data visualization.
Inspiration from various sources on recommendation systems and machine learning techniques.
