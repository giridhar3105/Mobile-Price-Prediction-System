# Mobile Price Prediction System

[![GitHub license](https://img.shields.io/github/license/giridhar3105/Mobile-Price-Prediction-System)](https://github.com/giridhar3105/Mobile-Price-Prediction-System/blob/main/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/giridhar3105/Mobile-Price-Prediction-System)](https://github.com/giridhar3105/Mobile-Price-Prediction-System/issues)
[![GitHub stars](https://img.shields.io/github/stars/giridhar3105/Mobile-Price-Prediction-System)](https://github.com/giridhar3105/Mobile-Price-Prediction-System/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/giridhar3105/Mobile-Price-Prediction-System)](https://github.com/giridhar3105/Mobile-Price-Prediction-System/network)

## Author
**CHENNURU GIRIDHAR**

## Date
**25 - 06 - 2024**

---

## Table of Contents
1. [Introduction](#introduction)
2. [Problem Statement](#problem-statement)
3. [Market/Customer/Business Need Assessment](#marketcustomerbusiness-need-assessment)
4. [Target Specifications](#target-specifications)
5. [External Search](#external-search)
6. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
7. [Applicable Regulations](#applicable-regulations)
8. [Applicable Constraints](#applicable-constraints)
9. [Business Opportunity](#business-opportunity)
10. [Concept Generation](#concept-generation)
11. [Tools Used](#tools-used)
12. [Business Model](#business-model)
13. [Operational Procedure](#operational-procedure)
14. [Statistics of Smartphone Market in India](#statistics-of-smartphone-market-in-india)
15. [Financial Equation](#financial-equation)

---

## Introduction

The Mobile Price Prediction System aims to cross-validate the price of a mobile phone based on its features. This system can help both consumers and manufacturers by providing an estimate of the price based on various parameters.

## Problem Statement

Mobiles have become integral to modern life, serving multiple purposes. Buyers often consider various parameters like brand, processor, memory size, camera, and battery backup but often overlook the price. The main objective is to introduce a system that predicts the price of a mobile phone based on its features.

## Market/Customer/Business Need Assessment

Price is a crucial aspect of shopping. Customers often want to know if the item is worth its price. This service will help customers estimate the price of a mobile before making a purchase.

## Target Specifications

The service will predict the mobile price based on:
- Brand
- Front & Rear Camera Megapixels
- RAM Capacity
- Internal Memory (ROM)
- Type of Android
- 3/4/5 G Support
- Number of Sim Card Support
- Battery Support (in mAh)

## External Search

- **Dataset**
- **Linear Regression**
- **Lasso and Ridge Regression**

## Exploratory Data Analysis (EDA)

(Insert detailed EDA visuals and descriptions here)

## Applicable Regulations

Many mobile manufacturing companies don’t allow scraping data from their official websites, which can hinder data collection.

## Applicable Constraints

The mobile market is always changing, so continuous data collection and updating are necessary to maintain model accuracy.

## Business Opportunity

This price prediction service can be useful for both customers and sellers, providing a benchmark price and helping to assess customer preferences.

## Concept Generation

### Algorithms

#### Linear Regression
Linear regression is used for predictive analysis, making predictions for continuous variables such as product prices.

#### Lasso and Ridge Regression
Lasso and Ridge regressions address overfitting by penalizing the magnitude of coefficients.

### Tools Used

- **Python**: Programming language for building the service.
- **Pandas**: Library for data handling and manipulation.
- **Beautiful Soup**: Web-scraping tool for fetching data from webpages.
- **Scikit-learn**: Library with algorithms for machine learning tasks.
- **Matplotlib and Seaborn**: Libraries for data visualization.

## Business Model

The service is based on a fee-for-service model, useful for both mobile manufacturers and customers, offering insight into fair pricing and customer preferences.

## Operational Procedure

The Price Predictor will be deployed as a web-based application, with various purchase options (one-time use, subscription, etc.). Feedback from users will help improve the algorithm over time.

## Statistics of Smartphone Market in India

- India’s smartphone shipments grew 9% YoY in Q2 2022.
- Xiaomi led the market with a 19% shipment share.
- 5G smartphones contributed to 29% of overall shipments.

## Financial Equation

Assuming the cost of developing the model includes salaries for two ML engineers and one full stack web developer:
\[ c = 2 \times ml + fs \]
The profit equation:
\[ y = 5000 \times x(t) - (2 \times ml + fs) \]
Where \( x(t) \) is the growth of the customer base and \( y \) is the profit.

---

## Usage

1. Clone the repository:
    ```sh
    git clone https://github.com/giridhar3105/Mobile-Price-Prediction-System.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Mobile-Price-Prediction-System
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/giridhar3105/Mobile-Price-Prediction-System/blob/main/LICENSE) file for details.

---

Feel free to reach out with any questions or feedback. Happy predicting!
