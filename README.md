# DS4002 Prototyping Project Cycle 2: Charlottesville Housing Prices and Their Relationship to Seasonality and Neighborhoods

## Software and Platform
- **Programming Language**: Python 3
- **Development Environment**: Google Colab
- **Libraries and Packages Used**:
  - *pandas* - for data manipulation and cleaning
  - *matplotlib* - to create data visualizations
  - *seaborn* - another visualization tool
  - *numpy* - for numerical computation

## Map of Documentation
- **Data**
  - **Cleaned Data**
    - Cleaned CSV files for Charlottesville housing market and each neighborhood pairing scraped (4 CSVs total) - output from Script 1_CleaningData.ipynb
  - **Uncleaned Data**
    - Uncleaned CSV files for Charlottesville housing market and each neighborhood pairing scraped (4 CSVs total)
  - Merged_Final_Data.csv - Merged and cleaned CSV containing all housing market data, regionally and by neighborhood
- **Scripts**
  - 1_Charlottesville_Cleaning.ipynb - script to clean Charlottesville data
    - Output: Cleaned_Charlottesville.csv
  - 2_Cleaning_Neighborhood_Data.ipynb - script to clean each neighborhood pair of uncleanded data (repeat for 3 neighborhood uncleaned csvs)
    - Output: cleaned neighborhood data (Cleaned_JeffersonParkFrySpring.csv etc.)
  - 3_Merging_Data.ipynb - script to combine all cleaned data (Charlottesville + neighborhood data)
    - Output: Merged_Final_data.csv
- **Output**
  - BoxPlot_Median_Sales.png
  - HeatMap_Prices_Belmont.png
  - HeatMap_Prices_Cville.png
  - HeatMap_Prices_Fifeville.png
  - HeatMap_Prices_FrySprings
  - HeatMap_Prices_JeffPark.png
  - HeatMap_Prices_MarthaJeff.png
  - HeatMap_Prices_Venable.png
  - LineGraph_Housing_Prices.png
  - Monthly_Housing_Summary.csv
  - ScatterPlot_HomesSoldvsPrices.png
  - ScatterPlot_Housing_Prices.png

## Instructions for Reproducing the Results
