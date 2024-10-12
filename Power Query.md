# Power Query for Excel

This repository provides an example of how to use Power Query in Excel to load, clean, and transform data. Power Query is an advanced tool for data manipulation, allowing you to automate data imports, transformations, and cleaning processes with ease.

## Features

- **Load Data:** Import data from various sources like Excel files, CSVs, databases, and web URLs.
- **Data Transformation:** Perform operations such as removing duplicates, filtering rows, replacing null values, and adding calculated columns.
- **Automation:** Streamline data workflows by automating repetitive tasks.

## Prerequisites

- **Microsoft Excel**: Power Query is available in Excel 2016 or later. For earlier versions, Power Query must be installed as an add-in.
- **Basic Excel Knowledge**: Familiarity with Excel's data management and formulas is recommended.

## Setup and Usage

### Step 1: Load Data into Power Query

1. Open your Excel file.
2. Go to the **Data** tab in the ribbon.
3. Click **Get Data** → **From File** → **From Workbook** (or choose your desired data source).
4. Browse to the file location and load the data into Power Query.

### Step 2: Open Power Query Editor

1. Once your data is loaded, click on **Transform Data** to open the Power Query Editor.
2. In this editor, you can clean and transform the data using a variety of built-in functions.

### Step 3: Apply Transformations

Here's a summary of the transformations performed in this example:
- **Remove Duplicates**: Eliminate duplicate rows from the dataset.
- **Filter Null Values**: Filter out rows where specific columns (e.g., sales) are empty or null.
- **Replace Nulls with Mean**: Replace null values in numeric columns with the column's mean value.
- **Add a Calculated Column**: Create new calculated columns based on existing data (e.g., calculating Total Sales =
