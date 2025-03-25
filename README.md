# DS4002 Prototyping Project Cycle 2: Charlottesville Housing Prices and Their Relationship to Seasonality and Neighborhoods

## Software and Platform
- **Programming Language**: Python 3
- **Development Environment**: Google Colab
- **Libraries and Packages Used**:
  - *pandas* - for data manipulation and cleaning
  - *matplotlib* - to create data visualizations
  - *seaborn* - another visualization tool
  - *numpy* - for numerical computation
  - *datetime* - to conduct time series analysis
- **Platform**: Mac

## Map of Documentation
- **Data**
  - **Cleaned Data**
    - Cleaned CSV files for Charlottesville housing market and each neighborhood pairing scraped (4 CSVs total) - output from Script 1_CleaningData.ipynb
  - **Uncleaned Data**
    - Uncleaned CSV files for Charlottesville housing market and each neighborhood pairing scraped (4 CSVs total)
  - Merged_Final_Data.csv - Merged and cleaned CSV containing all housing market data, regionally and by neighborhood
  - DataAppendix.pdf
- **Scripts**
  - 1_Charlottesville_Cleaning.ipynb - script to clean Charlottesville data
    - Output: Cleaned_Charlottesville.csv
  - 2_Cleaning_Neighborhood_Data.ipynb - script to clean each neighborhood pair of uncleaned data (repeat for 3 neighborhood uncleaned CSVs)
    - Output: cleaned neighborhood data (Cleaned_JeffersonParkFrySpring.csv etc.)
  - 3_Merging_Data.ipynb - script to combine all cleaned data (Charlottesville + neighborhood data)
    - Output: Merged_Final_data.csv
  - 4_Exploratory_Graphs.ipynb - script for EDA and visualizations, in order to understand relationships between median housing price, seasonality, and neighborhood
    - Output: BoxPlot_Median_Sales.png, HeatMap_Prices_Belmont.png, HeatMap_Prices_Cville.png, HeatMap_Prices_Fifeville.png, HeatMap_Prices_FrySprings.png, HeatMap_Prices_JeffPark.png, HeatMap_Prices_MarthaJeff.png, HeatMap_Prices_Venable.png, LineGraph_Housing_Prices.png, ScatterPlot_HomesSoldvsPrices.png, ScatterPlot_Housing_Prices.png, ScatterPlot_MedianSalePriceMonthly.png
  - 5_Data_Appendix.ipynb - script to create data appendix:
      - Output: DataAppendix.pdf
  - 6_Linear_Regression.ipynb - script to create a linear regression model, which gave us insight into the relationship between median housing prices, seasonality, and neighborhoods
  - 7_Cluster_Analysis.ipynb - script to analyze relationships and trends between median housing prices and months/seasons
      - Output: Seasonal_Clustering_of_Median_Home_Prices.png
- **Output**
  - Actual_vs_Predicted_Cville_Median_Housing_Prices.png
  - BoxPlot_Median_Sales.png
  - Distribution_of_Dates.png
  - Distribution_of_Homes_Sold.png
  - Distribution_of_Homes_Sold_MoM.png
  - Distribution_of_Homes_Sold_YoY.png
  - Distribution_of_Location.png
  - Distribution_of_Median_Sale_Price.png
  - Distribution_of_Median_Sale_Price_MoM.png
  - Distribution_of_Median_Sale_Price_YoY.png
  - HeatMap_Prices_Belmont.png
  - HeatMap_Prices_Cville.png
  - HeatMap_Prices_Fifeville.png
  - HeatMap_Prices_FrySprings
  - HeatMap_Prices_JeffPark.png
  - HeatMap_Prices_MarthaJeff.png
  - HeatMap_Prices_Venable.png
  - Homes_Sold_vs_Median_Home_Prices.png
  - LineGraph_Housing_Prices.png
  - Median_Sale_Prices_Across_All_Locations.png
  - Monthly_Housing_Summary.csv
  - Neighborhood_Clustering_by_Median_Home_Prices.png
  - Predicted_Median_Housing_Prices_by_Month_in_Cville.png
  - References.md
  - SARIMA_Forecast_of_Cville_Median_Sale_Price.png
  - ScatterPlot_HomesSoldvsPrices.png
  - ScatterPlot_Housing_Prices.png
  - ScatterPlot_MedianSalePriceMonthly.png
  - Seasonal_Clustering_of_Median_Home_Prices.png

## Instructions for Reproducing the Results
1. Clean the Uncleaned_RedfinCharlottesvilleHousingMarket.csv file found in DATA/Uncleaned Data using 1_Charlottesville_Cleaning.ipynb
2. Clean the 3 neighborhood datasets (Uncleaned_FifevilleMarthaJefferson.csv, Uncleaned_JeffersonParkFry Spring.csv, VenableData_Unclean.csv) found in DATA/Uncleaned Data using 2_Cleaning_Neighborhood_Data.ipynb (repeat for each neighborhood)
3. Merge the 4 cleaned datasets using the 3_Merging_Data.ipynb
4. Conduct exploratory data analysis, creating visualizations such as scatterplots, boxplots, and heat maps, using the 4_Exploratory_Graphs.ipynb script
5. Create a linear regression model using 6_Linear_Regression.ipynb, and make predictions on future median housing prices, whether for Charlottesville regionally or by neighborhood
6. Analyze relationships and trends between median home sale prices and seasons using 7_Cluster_Analysis.ipynb
7. Test against our hypothesis and draw conclusions
