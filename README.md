# Forecasting-project

Scenario 1: Hydrological Forecast
Problem:  
          Given 576 observations at a monthly resolution of the level of a body of water,
          Forecast 24 months ahead the series with 95% prediction intervals
          
Result:[a link](https://github.com/nlb13x/Forecasting-project/blob/main/Scenario1.pdf)

Scenario 2: Financial Risk Forecast
Problem:  
          Given 150 daily resolution log-differenced price data from 40 stocks on NYSE
          Forecast 15% quantiles 10 steps ahead for each series (in other words, forecasts
          for Value-at-Risk)

Scenario3&4: Multivariate Time Series Forecasting
Problem:  
          Given time series of beer, car, steel, gas, electricity production and mean high
          temperautres of Australia
          Forecast 24 months ahead the beer production in Australia with 95% prediction intervals

Scenario5: Long Horizon Pollution Forecasting
Problem:  
          Given half-hourly measurements of the concentration of an air pollutant in three
          different cities over 53 day
          Forecast each stock series 1 to 366 half-hourly steps ahead, which corresponds to 
          one week ahead along with 95% prediction intervals
          

- forecasting_results : forecasting results for each scenario
- scenario_{} : dataset for each scenario and corresponding R files
- scenario{}.pdf : reports for each scenario explaining the model I chose for the scenario and how I assessed the models using goodness of 
                    fit test and cross validation
