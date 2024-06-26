# Chinook Data Analysis Project

![Untitled design](https://github.com/VwedeOkojie/Chinook/assets/161823174/f3e4db09-0ad4-4ea0-9441-4aba52f6a2f1)


## Project Description

This project aims to analyze sales data from the Chinook database to gain insights into sales trends, customer behavior, and other key metrics to understand the business performance.

## Data Extraction

The project uses sales data sourced from the Chinook database, which provides detailed information about sales transactions, customer demographics, and product details.

## Technologies Used

- SQL
- Python (for data processing and visualization)

## Data Processing

- **Cleaning the Dataset:**
  - Handling missing values
  - Removing duplicates
- **Transforming the Data:**
  - Structuring the data into a format suitable for analysis

## Data Loading

- Loading the cleaned data into a SQL database

## Analysis and Insights

### Total Sales Analysis

#### Annual Sales Trends
![Annual Sales Over Time](https://github.com/VwedeOkojie/Chinook/assets/161823174/eabf0296-0a53-4af3-9a41-91683cdf54e1)


This line chart tracks the annual sales over the years. It shows a peak in 2022, followed by fluctuations in subsequent years.

#### Top-Selling Genres and Countries
![Top 5 Contries by Total](https://github.com/VwedeOkojie/Chinook/assets/161823174/67a402f0-4d40-442b-a2e2-635239f050c3)


This bar chart displays the total revenue generated from music sales in the top 5 countries. The USA leads significantly, followed by Canada and France.

#### Top-Selling Genres in Canada
![Genre Sales in Canada](https://github.com/VwedeOkojie/Chinook/assets/161823174/8b1244d9-bcbd-4b60-9767-4a23c6ab3626)


This bar chart illustrates the sales of different music genres in Canada. Rock and Latin genres dominate the sales figures.

### Customer Analysis

#### Top Customers by Total Sales
![Top 10 Customers](https://github.com/VwedeOkojie/Chinook/assets/161823174/66c211ea-f743-4a8b-b2a8-fc5f80460356)


This bar chart highlights the top 10 customers based on their total spending. Helena Holý and Richard Cunningham are the top spenders.

### Product Analysis

#### Top-Selling Artists and Tracks
![Top 10 Tracks by Total Sales](https://github.com/VwedeOkojie/Chinook/assets/161823174/97fd7050-553c-48d8-9eb5-4dbaa08c1f3e)


This bar chart shows the top 10 tracks by total sales. "Dazed And Confused" and "The Trooper" lead the list, indicating high popularity and sales performance.

#### Top Artist
![Top Artist](https://github.com/VwedeOkojie/Chinook/assets/161823174/48f70283-43af-4771-baeb-9818b0af807c)


This bar chart shows the top artist by the number of playlist appearances. Iron Maiden is the leading artist with the highest number of appearances.

#### Revenue by Genre and Country
![Revenue and Units Sold](https://github.com/VwedeOkojie/Chinook/assets/161823174/9e7faf2e-2ba6-40c6-9b03-924a48892f6b)


This scatter plot illustrates the total revenue and units sold for different genres across various countries. The size of the bubbles represents the number of units sold, with the USA and Rock genre showing the highest sales and revenue.

#### Top 3 Employees
![Top Employees](https://github.com/VwedeOkojie/Chinook/assets/161823174/d5115632-7ae0-42e1-9b9e-1e3ef06cef94)


This bar chart ranks the top 3 employees by their total sales. Jane Peacock leads the chart, followed by Margaret Park and Steve Johnson.


## How to Use the Project

1. **Download the Dataset:**
   - Get the Chinook database from the provided source.
   
2. **Clean and Preprocess the Data:**
   - Use Python for data cleaning and preprocessing if necessary.
   
3. **Load the Data into a SQL Database:**
   - Use SQL scripts to load the cleaned data into the database.
   
4. **Run SQL Queries:**
   - Analyze the data and extract insights using the provided SQL scripts.

5. **Run Python Codes:**
   - Use the following command to run the Jupyter Notebook for Python scripts:
     ```sh
     jupyter notebook Python\ Script.ipynb
     ```

## Project Structure

- [Chinook SQL Commands and Visualization.ipynb](https://github.com/VwedeOkojie/Chinook/blob/7c83d0fb991d52c99b6e56433213cdb3ae7aa365/Chinook%20SQL%20Commands%20and%20Visualization.ipynb) - Jupyter Notebook for SQL commands and visualizations
- [Dataset](https://github.com/VwedeOkojie/Chinook/blob/7c83d0fb991d52c99b6e56433213cdb3ae7aa365/Dataset) - Folder containing the Chinook database file
- [Python Script.ipynb](https://github.com/VwedeOkojie/Chinook/blob/7c83d0fb991d52c99b6e56433213cdb3ae7aa365/Python%20Script.ipynb) - Jupyter Notebook for Python script
- [README.md](https://github.com/VwedeOkojie/Chinook/blob/7c83d0fb991d52c99b6e56433213cdb3ae7aa365/README.md) - Project overview and instructions `You are here`
- [SQL Script](https://github.com/VwedeOkojie/Chinook/blob/be10354b39abd411633bfaa284b4169d47aa1318/SQL%20Script) - Folder containing SQL scripts for data loading and analysis

## Contributing

Contributions are welcome via pull requests. Please follow the contribution guidelines in the repository.

## License

The project is licensed under MIT License.

## Contact Information

You can reach out to [vwedeokojie@gmail.com](mailto:vwedeokojie@gmail.com) for questions, collaboration, or more information about this project.
