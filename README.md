# Assignment10


# Question No. 1

## Datasets

Dataset 1 : wholesalegasolineprices
Link : https://data.ontario.ca/dataset/wholesale-gasoline-prices-toronto-and-new-york-harbor



Dataset 2 : GHG_Data_2010_2020_data_Dec162021
Link : https://data.ontario.ca/dataset/?keywords_en=Economy+and+Business&res_format=CSV&page=2

Justification to use dataset 1

The "wholesalegasolineprices" dataset appears to be useful for machine learning tasks, particularly those involving energy and fuel price analyses. The dataset contains multiple columns pertaining to wholesale petrol prices in various locations on various dates.

Justification for choosing a dataset:

1. Analytical Potential: This dataset contains historical wholesale petrol prices for many locales, including Toronto and Thunder Bay, as well as similar prices from New York Harbour and Edmonton. It provides a wealth of data for analysing pricing trends, price differences across places, and the influence of changes in external markets (New York Harbour and Edmonton) on local petrol prices in Toronto and Thunder Bay.


2. Machine Learning Application Suitability: The dataset is well-suited for machine learning applications. Based on previous data, it can be used to create predictive models that project future wholesale petrol prices. Furthermore, the dataset enables regression analysis to better understand the relationship between wholesale prices in various regions and spot prices from New York Harbour and Edmonton. Price trends and odd price changes can also be identified using clustering and anomaly detection techniques.

Overall, the "wholesalegasolineprices" dataset has the potential to provide useful insights and prediction capabilities for energy enterprises and regulators. It can assist in making informed judgements about wholesale petrol pricing, supply chain management, and market dynamics. However, the data must be cleaned and preprocessed. 


Justification to use dataset 2
The dataset "GHG_Data_2010_2020_data_Dec162021" appears to be relevant for machine learning tasks in the context of analyzing and predicting greenhouse gas (GHG) emissions for various facilities in Ontario over the years 2010 to 2020.

This dataset has several features (columns) related to GHG emissions, such as carbon dioxide (CO2) from non-biomass, CO2 from biomass, methane (CH4), nitrous oxide (N2O), sulphur hexafluoride (SF6), hydrofluorocarbons (HFCs), perfluorocarbons (PFCs), nitrogen trifluoride (NF3), and total CO2e from all sources. Each of these features represents emissions in CO2e (carbon dioxide equivalent) units, which helps measure the global warming potential of the emissions.

The dataset includes information about various facilities, such as the facility owner, facility name, facility city, and primary NAICS code (North American Industry Classification System code). This additional information allows for analysis and comparison of emissions across different types of facilities.

The dataset spans over ten years, which provides a temporal dimension to the data. Temporal data can be useful for analyzing trends, seasonality, and changes in emissions over time.

With this dataset, machine learning tasks such as regression, time-series forecasting, and classification can be performed. For example:

1. Regression: Predicting the total CO2e emissions based on different emission sources, facility types, or other factors.
2. Time-Series Forecasting: Forecasting GHG emissions for future years based on historical data.
3. Classification: Classifying facilities into different emission categories based on their GHG emissions.

Overall, this dataset holds great potential for analyzing and understanding GHG emissions trends in Ontario over the past decade and can be used to build predictive models to aid in environmental and sustainability studies. However, it is essential to ensure data quality, handle missing values, and preprocess the data appropriately before applying machine learning algorithms.

Instruction to run the code
1. Go to https://github.com/Rony109/Assignment10
and download the pynb file, place it in the software along with the dataset
and execute it


