# T20-World-Cup-Cricket-Data-Analytics-Project

This project focuses on analyzing T20 World Cup cricket data to select the best 11 players for defeating an alien cricket team. It involves web scraping, data cleaning, transformation using Python and Pandas, and data visualization using Power BI.

## Key Parameters for Player Selection

The key parameters used to select the best 11 players for the cricket team are:

- Batting average
- Strike rate
- Boundary percentage
- Innings batted
- Bowling strike rate
- Bowling average
- Economy rate
- Dot balls produced
- Consistency in performance

These parameters are crucial for evaluating players' performance in both batting and bowling to create a well-balanced team for the T20 World Cup.

## Data Transformation from JSON to CSV Files

The data transformation from JSON to CSV files using Python and Pandas is performed as follows:

1. **Loading JSON Data**: The JSON data is loaded into a Pandas DataFrame using `pd.read_json()`.

2. **Data Cleaning and Transformation**:
   - Renaming columns
   - Creating new columns based on existing data (e.g., calculating batting averages, strike rates, etc.)
   - Handling special characters in the data

3. **Exporting to CSV**: Once the data is transformed, it is exported to a CSV file using `df.to_csv()`.

The process involves using various Pandas methods such as `json.load()`, `apply()`, `rename()`, `drop()`, `replace()`, and `map()` to manipulate the data effectively.

## Usage

1. **Web Scraping**: Data is scraped from ESPNcricinfo using Bright Data for efficient web scraping.
   
2. **Data Analysis**: Data is imported into Jupyter Notebook, where it undergoes further analysis, cleaning, and transformation.

3. **Visualization**: Power BI is used to visualize the insights and create a dashboard for analyzing player statistics.

## Contributing

Contributions to this project are welcome! If you'd like to contribute, please follow these steps:
   
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/yourfeature`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add some feature'`).
5. Push to the branch (`git push origin feature/yourfeature`).
6. Create a new Pull Request.

## License

This project is licensed under the [MIT License](LICENSE).

