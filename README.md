# Analyzing-Data-with-Pandas-and-Visualizing-Results-with-Matplotlib
# Global CO2 Emissions Analysis Project

This project analyzes global CO2 emissions data using Python's data analysis and visualization libraries. The analysis focuses on understanding trends in CO2 emissions, their relationship with economic development, and patterns across different countries.

## Dataset Information

The project uses the "Our World in Data CO2 and Greenhouse Gas Emissions" dataset, which includes:
- Annual CO2 emissions data from 2000 to present
- Data for all countries worldwide
- Multiple metrics including total emissions, per capita emissions, and GDP

### Key Variables Used
- `country`: Country name
- `year`: Year of the data
- `co2`: Annual CO2 emissions (million tonnes)
- `gdp`: GDP in international dollars
- `population`: Total population
- `co2_per_capita`: CO2 emissions per person

## Project Structure

```
.
├── data_analysis.py      # Main analysis script
├── requirements.txt      # Python package dependencies
├── co2_emissions.csv     # Dataset file
├── visualizations.png    # Generated visualizations
└── README.md            # Project documentation
```

## Setup Instructions

1. **Install Python Dependencies**
   ```bash
   python -m pip install -r requirements.txt
   ```

2. **Download the Dataset**
   The dataset is automatically downloaded when running the script. It's sourced from:
   [Our World in Data CO2 and Greenhouse Gas Emissions](https://github.com/owid/co2-data)

3. **Run the Analysis**
   ```bash
   python data_analysis.py
   ```

## Analysis Features

### 1. Data Processing
- Loads and cleans the CO2 emissions dataset
- Filters data from 2000 onwards
- Handles missing values appropriately

### 2. Exploratory Data Analysis (EDA)
- Generates statistical summaries of key variables
- Provides data information and structure
- Shows sample data for initial inspection

### 3. Visualizations
The script creates four different visualizations:

1. **Global CO2 Emissions Trend (Line Chart)**
   - Shows the total global CO2 emissions over time
   - Helps identify overall trends and patterns

2. **Top 10 Emitting Countries (Bar Chart)**
   - Displays the countries with highest average CO2 emissions
   - Enables comparison between major emitters

3. **CO2 Emissions per Capita Distribution (Histogram)**
   - Shows the distribution of per capita emissions
   - Helps understand the spread of emissions across countries

4. **CO2 vs GDP Relationship (Scatter Plot)**
   - Illustrates the correlation between economic development and emissions
   - Helps identify patterns in economic-emission relationships

## Output

The script generates:
- Console output with statistical summaries and key findings
- `visualizations.png` containing all four plots
- Key insights about global CO2 emissions patterns

## Key Findings

1. The dataset provides comprehensive CO2 emissions data from 2000 to present
2. Visualizations reveal global trends in CO2 emissions and their relationship with economic development
3. Analysis shows patterns in emissions per capita and correlations with GDP
4. Data enables comparison of emissions across different countries and time periods

## Requirements

- Python 3.x
- pandas
- matplotlib
- seaborn
- numpy

## Future Improvements

Potential enhancements for the project:
- Add more advanced statistical analysis
- Include additional visualization types
- Implement interactive plots
- Add export functionality for analysis results
- Include more detailed country-specific analysis

## License

This project uses data from Our World in Data, which is available under the Creative Commons BY license.
