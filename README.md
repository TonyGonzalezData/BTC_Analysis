# BTC_Analysis
Analyze whether top cryptocurrencies follow BTC's price patterns or act independently, and identify those with higher returns and lower volatility for mid-to-long-term investment.

## Objective

This analysis aims to identify whether the top cryptocurrencies by market capitalization follow a price pattern similar to Bitcoin (BTC), indicating a dependency, or if they operate independently, driven by their own market dynamics. Additionally, the study seeks to determine which of these cryptocurrencies offer the potential for higher returns while maintaining lower risk, measured as lower volatility, for mid-to-long-term investment strategies.

> [!NOTE]  
> The most recent data is from 19/11/2024.
> 
> You can access the notebooks directly in this [folder](https://github.com/TonyGonzalezData/BTC_Analysis/tree/main/03_Notebooks/01_Development).


## About the Dataset

The dataset was created using Kline data, market capitalization, and price information as of 19/11/2024, obtained through the Binance API.

The data was then cleaned, organized, and merged in the data quality phase.


## Project Structure

The development of the Discovery project consists of the following structure:

- **Project design**: We define the objectives, KPIs, and seed questions.
- **Set up**: We load the data from its original sources and save it in pickle format.
- **Creation of the Analytic Datamart**: Data cleaning, including review of data types and transformation of variables, handling of duplicates and null values, EDA of categorical and numerical variables, and finally, the construction of the analytic datamart.
- **Data preparation**: Creation of the synthetic variables necessary to shape the KPIs defined in the Project design phase.
- **Analysis**: Study of the final data and generation of insights.

## Conclusions

The final report with conclusions on the BTC and Crypto Market Analysis can be found directly at this public Tableau link: [BTC and Crypto Market Analysis](https://public.tableau.com/app/profile/antonio.gonz.lez.pazos/viz/BTCandCryptoMarketAnalysis/Intro)


> [!NOTE]  
> The project was developed using data dated November 19, 2024.
> 
> Therefore, some of the insights and conclusions are only relevant within this time frame.
> 
> The same applies to the Tableau Dashboard, which reflects the information from that date.
