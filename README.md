# Blood Donation Prediction Using TPOT

## Overview
This project utilizes the Tree-based Pipeline Optimization Tool (TPOT) to predict whether individuals are likely to donate blood. TPOT automates the process of selecting the best machine learning pipeline, focusing on feature preprocessing, model selection, and parameter tuning.

## Dataset
The dataset used in this project includes several features related to blood donation history from a mobile blood donation vehicle.

## Features
- **Recency**: Time since last donation
- **Frequency**: Total number of donations
- **Monetary**: Total blood donated
- **Time**: Months since the first donation
- **Target**: Whether the individual donated blood in March 2007 (binary: 1=yes, 0=no)

## Installation
To run this notebook:
1. Clone the repository:
   ```bash
   git clone https://github.com/hamasakram/AutoML.git
2. Install the required packages:
   
   pip install tpot pandas numpy matplotlib sklearn

 
