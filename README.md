# Walmart Sales Data - Exploratory Data Analysis (EDA)

![Walmart Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/Walmart_logo.svg/1200px-Walmart_logo.svg.png)

## Overview

This repository contains an exploratory data analysis (EDA) project on Walmart sales data. The goal of this project is to understand the sales patterns, identify key trends, and derive insights that could help in decision-making processes.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Key Findings](#key-findings)

## Dataset

The dataset used in this project includes historical sales data from Walmart. The data has the following columns:

- `InvoiceID`: Invoice id
- `Branch`: City branch name
- `City`: Name of the city
- `Customer type`: Type of customer. Either Member or non-member(Normal)
- `Gender`: Gender type. Male or Female
- `Product line`: Product category
- `Unit Price`: Product price
- `Quantity`: Number of product purchased
- `Date`: Date of purchase
- `Time`: Time of purchase
- `Payment`: Payment type
- `Rating` - Rating of a product

## Installation

To run this project, you need to have Python installed along with some essential libraries. Follow the steps below to set up your environment:

1. Clone the repository:
   ```sh
   git clone https://github.com/nbljain/Walmart_Sales_Analysis.git
   cd Walmart_Sales_Analysis

2. Create environment:
   ```sh
   python -m venv env
   source env/bin/activate

3. Install dependencies:
   ```sh
   pip install -r requirements.txt

## Usage

To start the analysis, you can open and run the Jupyter Notebook:

- Open the **Walmart_Sales_Analysis.ipynb** notebook and run the cells to see the analysis.

## Project Structure

1. The structure is as follows:
      ```sh
         Walmart_Sales_Analysis/
         │
         ├── data/
         │   ├── Walmart Sales.xlsx             # Walmart sales data
         │
         ├── notebooks/
         │   └── Walmart_Sales_Analysis.ipynb   # Jupyter notebook containing the EDA
         │
         ├── requirements.txt                   # Required Python packages                     
         └── README.md                          # Project README file

## Key Findings

Some of the findings are:

- City `Naypyitaw` has the highest total revenue generated.
- City `Yangon` has the highest total sales.
- City `Yangon` has highest total sales in city `B` with highest total revenue.
- City `Naypyitaw` has the highest total sales in the city `A` and has the highest total revenue.
- City `Mandalay` has highest total sales in city `B` with highest total revenue.
- City `Yangon` has the highest total sales for the product under `Home and lifestyle` and the lowest total sales for the `Health and beauty` category.
- City `Naypyitaw` has the highest total sales for the product under `Food and beverages` and the lowest for the `Home and lifestyle` category.
- City `Mandalay` has the highest total sales for the product under `Sports and travel` and the lowest total sales for the `Food and beverages` category.
- City `Yangon` has the highest total sales made under the `Male` category, whereas the other two cities have more sales made under the `Female` category.
- City `Yangon` has the highest total revenue from payment type `Ewallet` and the lowest from `Credit card`.
- City `Naypyitaw` has the highest total revenue from payment type `Cash` and the lowest from `Credit card`.
- City `Mandalay` has the highest total revenue from payment type `Credit card` and the lowest from `Ewallet`.
- All three cities have the highest total revenue from the `Member` Customer type.
- Product under category `Home and lifestyle` has maximum contribution towards sales and revenue made in **Month 3**.
- Payment `Ewallet` has maximum contribution towards sales and revenue from **Month 1**.
