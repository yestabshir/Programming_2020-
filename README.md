# Programming_2020- 
## A) Inaugral Project: 
      Basic Labor Supply problem of Macroeconomic Model using numpy, scipy and matplotlib
  1.1: Define obejctive function, define tax and define budget constraint, define consumer choice 
       and define maximisation using optimize minimize scalar to get the results.
  1.2: Usine range from question 2 plot the figure
  1.3: Solve tax revenue
  1.4 Calculate utility of consumption and labor price, also find optimal labor supply choice ~ Calculation is same as 1.1
 
 
 
 ## B) Data Analysis Project: 
  1. Project Description:  How does unemployment rate of different genders change from 1990 and how it relates to the GDP per capita
  2. Data Processing, Data Fetching and Data Merging:  I first fetch the GDP data include GDP in purchasing power pariety and GDP growth rate from world bank database website by using API, also fetch unemployment rates for both male and female in those countries and merge 2 data sets together
  3. Explore Data Set: In order to be able to explore the raw data, provide both static interactive plot to show gdp growth rate and unemployment rate for both male and female in each country
  4. Analysis: Use groupby and describe to calculte mean and standard deviation of unemployment rate for male and female
  5. Conclusion: In the first part fetch unemployment data and GDP growth data from world bank database, combine 2 datasets into a new dataset called 'data' and remove    the rows with missing. Then drew static plots and intercative plots and find out the changing pattern of average unemployment rates. I have noticed that the average unemployment rate for different Asian countries are different, China, Japan and Vietnam have relatively higher overtime male unemployment rate while the other Asian countries have higher female unemployment rate. The dispersion of unemployment rates in different countries are different as well, Indonesia and Korea has exceptionally high fluctuation in female and male unemployment. Lastly I have not obeserved the correlation relation between GDP per capita, thus the cause of unemployment rate can not be clarified in this project.


## C) Model Project: 
In this project I have first solved the Intertemporal Consumer Optimization problem numerically, then I have introduce Ramsey model with cobb-douglas production function of firms and log utility of consumers. We have found that both numerical result and analytical results for optimal value of k and c are 0.6284 and 0.7676 with given values of variables. I have also plotted the phase diagram of the model and the changing of consumption by giving initial of capital. I observed given initial values of capital $k_0$ = 1.000 and consumption $c_0$ = 1.0117 the economy will reach balanced growth path. 
