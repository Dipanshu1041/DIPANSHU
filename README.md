# DS
# Python Data Analysis: NumPy Operations & T20 Cricket EDA

**Author:** DIPANSHU RAWAT

## Overview
This repository contains a comprehensive Python script that serves as a dual-purpose data science pipeline. It first demonstrates advanced, multi-dimensional array manipulations using NumPy. The second half of the pipeline ingests an International T20 Cricket dataset to perform data cleaning, transformation, and Exploratory Data Analysis (EDA) using Pandas, Matplotlib, and Seaborn.

## Features

### 1. Advanced Matrix & Tensor Operations (NumPy)
* **Array Generation:** Creation of 2D matrices and 3D tensors using randomized data.
* **Structural Manipulation:** Implementations of `.transpose()`, `.reshape()`, `.resize()`, and `.flatten()`.
* **Data Modification:** Inserting, appending, and deleting elements across specific axes (Axis 0, 1, and 2).
* **Mathematical Broadcasting:** Matrix multiplication, division, statistical aggregations (min, sum), and sorting algorithms.

### 2. Data Processing Pipeline (Pandas)
* **Ingestion:** Importing structured CSV data (`International_T20_Data.csv`) while handling bad lines.
* **Cleaning:** Handling null values, dropping redundant columns (e.g., `meta.data_version`), and removing duplicates.
* **Transformations:** Lambda functions for string manipulation and custom mathematical operations.
* **Datetime Operations:** Utilizing `datetime` and `timedelta` to manipulate timestamp data and measure time intervals.
* **Sub-setting & Filtering:** Boolean indexing and targeted slicing utilizing `.loc` and `.iloc`.

### 3. Exploratory Data Analysis & Visualizations (Matplotlib & Seaborn)
* **Distributions:** Histograms and distribution plots (`sns.displot`) showing run margins and overs.
* **Categorical Comparisons:** Bar charts (Toss Decisions, Top Winning Teams) and Pie charts (Gender distributions).
* **Statistical Spread:** Box plots and Violin plots mapping run margins across male and female match types.
* **Trend Analysis:** Single and multi-line plots mapping match variables over time/index.
* **Correlation:** Heatmap generation mapping the correlation coefficients between all numeric variables.

## Requirements
To run this script, ensure you have Python 3.x installed along with the following libraries:
* `numpy`
* `pandas`
* `matplotlib`
* `seaborn`

## Usage
1. Ensure the `International_T20_Data.csv` file is located in the same directory as the script (or update the file path in the script to point to your data source).
2. Execute the script via your terminal or IDE:
   ```bash
   python main_script.py
