# Trends in APMC

Filtering outliers, detecting seasonality type, deseasonal prices , comparing MSP and de-seasonalize prices and price fluctuations in commodities using the two input files - CMO_MSP_Mandi.csv and Monthly_data_cmo.csv

Python Libraries used are : Pandas, Numpy, Matplotlib, Seaborn and Statsmodels

Input Files: CMO_MSP_Mandi.csv and Monthly_data_cmo.csv

Output Files: Output.zip 

## Process

1. Importing the modules.

2. Imporing the csv files through Pandas.

3. Plotting box plots to find outliers and removing them.

4. Cleaning the data by removing the price values that are 0 and applying filter with max_price should be geater than modal_price and modal_price should be greater than min_price.

5. Clustering data in dataframe for each cluster of APMC and Commodity and storing dataframes in a dictionary.

6. Finding seasonality in modal_price data for each APMC-Commodity combination, de-seasonalize price and price fluctuation using statsmodels python library.

7. Saving the each dataframe from a dictionary as a separate file in Output folder.


