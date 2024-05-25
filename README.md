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
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

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
   git clone https://github.com/yourusername/walmart-sales-eda.git
   cd walmart-sales-eda

2. Create environment:
   ```sh
   python -m venv env
   source env/bin/activate

3. Install dependencies:
   ```sh
   pip install -r requirements.txt

## Usage

To start the analysis, you can open and run the Jupyter Notebook:

- Open the **Walmart_Sales_EDA.ipynb** notebook and run the cells to see the analysis.

## Project Structure
```sh
walmart-sales-eda/
│
├── data/
│   ├── walmart_sales.csv         # Walmart sales data
│
├── notebooks/
│   └── Walmart_Sales_EDA.ipynb   # Jupyter notebook containing the EDA
│
├── images/
│   ├── sales_trends.png          # Example plot images
│
├── requirements.txt              # Required Python packages
├── README.md                     # Project README file
└── LICENSE                       # License file
