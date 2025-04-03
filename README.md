# Diamond Dataset Analysis in R

## Repository Overview
This repository contains an analysis of the Diamond dataset using R. The repository includes:
- `Diamond.csv`: The dataset used for analysis.
- `Diamond.r`: The R script that performs various operations on the dataset.
- `Rplots.pdf`: A PDF file containing visualizations generated during the analysis.

## Files
- **Diamond.csv**: A CSV file containing the Diamond dataset.
- **Diamond.r**: An R script that reads and explores the dataset.
- **Rplots.pdf**: A PDF file containing boxplot visualizations of the dataset.

## R Script Overview
The `Diamond.r` script performs the following operations:

1. **Set and Get Working Directory**
   - `setwd("path/to/directory")`  
   - `getwd()`  

2. **Read the CSV File**
   - `data <- read.csv("Diamond.csv")`

3. **Basic Dataset Information**
   - `dim(data)`: Get the dimensions (rows and columns) of the dataset.
   - `nrow(data)`: Get the number of rows.
   - `ncol(data)`: Get the number of columns.

4. **Preview Data**
   - `head(data)`: View the first few rows of the dataset.
   - `tail(data)`: View the last few rows of the dataset.

5. **Structure of Data**
   - `str(data)`: Get the structure of the dataset, including data types of each column.

6. **Summary Statistics**
   - `summary(data)`: Get summary statistics of the dataset.

7. **Check for Missing Values**
   - `sum(is.na(data))`: Count the number of missing values in the dataset.

8. **Boxplot Visualization**
   - `boxplot(data$carat)`: Generate a boxplot for the `carat` column.
