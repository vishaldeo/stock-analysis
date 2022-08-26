# Green Stock Analysis

## Overview of Project

Steve a college graduate, helping his customer  to genearate the analysis of green energy stocks. His customer want to invest in the green energy stock. As a financial advisor, Steve need to run the analysis of multiple green energy tickers and provide the summary of market trend of green energy stocks for prior years. 

Steve uses VBA to analysis the stock data. When the report run for a speicific Year, it generates the ticker Yearly summary 
* Total Volume of Share traded for that year
* % Return of the Stock
* The report represent the data more informational , it shows the percentage return as Profit / Loss based on the assumption the user invested at the first day of the financial year.

### Code Refactor for effciency

The analysis was to refactor the code that Steve wrote for the customer for optimal resource utilization and more efficient. Currenly Steve is using only green energy stock for analysis that would serve the puprose. If customer change the requirement to use Entire market data analysis by multiple financial domain the code should be efficient.   

## Results

### Prior Year 2017 & 2018 Stock Performances

#### 2017


![2017 Performances](/Resources/Stock_Analysis_2017.jpg?raw=true "Title")
 
 #### 2018

![2018 Performances](/Resources/Stock_Analysis_2018.jpg?raw=true "Title")
 



### Aanlysis on prior year data

Steve selected 12 Green energy stocks for analysis. As per the 2017/2018 performance we noticed that 2017 year was better for most of the stock than 2018. In 2017 only 1 stock ( `TERP`) perfome in loss ( `-7.2%`) and the best perfomer for 2017 was ( `DQ --> 199.4%` ) In 2018 , the best performing was ( `RUN --> 84.0%` )  and the worst performer was (`DQ --> -62.6%`) DQ with a -62.6% return. Based on the data if any user who intevested in the `ENPH` stock for 2 year it will generate `~400%` retrun overall. 

### Original Script Performance Versus Refactored Script Performance

#### Non-Refactored Script Performance
![2017 Analysis Speed](Resources/VBA_Challenge_2017_OldCode.jpg?raw=true "Title") 

![2018 Analysis Speed](Resources/VBA_Challenge_2018_OldCode.jpg?raw=true "Title")

#### Refactored Script Performance
![2017 Analysis Speed](Resources/VBA_Challenge_2017.jpg?raw=true "Title") 

![2018 Analysis Speed](Resources/VBA_Challenge_2018.jpg?raw=true "Title")

####  Script Performance Analysis

| Financial Year      | All Stock Analysis Perfomance |All Stock Analysis Refactored | % Performace |
| ----------- | ----------- |----------- |----------- |
| 2017    |     0.6015   |  0.1093  | 500% Faster |
| 2018     |  0.6171      | 0.1406 |  476% Faster |




## Summary

### Refactoring Code: Advantages / Disadvantage

#### Why we need refactor the code
As we are working on the timeline based project in every field , sometime the developer adapt the easy way to complete the project and doen't follow the programming best practices and meet the deadlines. The code will be good for a very specific use case or to perform on a small data set. 

The main advantage of refactoring code is that programmers often use it to make the code easy to understand and follow the architecture guidelines. The reason this is beneficial is because it makes the program faster/more efficient and use optimal system resources. 

#### Disadvantage 
The main disadvantages of refactoring code are that it can be time consuming and it is used for a very specific use case by the client. The refactoring require more man hours and client don't need any modification. That can be used under the techincal debt ( If company really want to do it and utilize the resources )

### Green Energy stock refactoring Code: Advantages / Disadvantage

This was a very first project for Steve ( Developer ) and for his client ( Parents) and based on the requirement Steve provided the deliverables. This analysis was run on  a very small dataset and serve the purpose. The analysis project was executing in less than a second which is good. It was easy and delivered fast ( within few hours ).

Scenario :
If Steve's clients are happy with the performace of the ticker provided and need more information on entire stock market , the code mayn't be delievered without using refactoring the code. It require to re-visit the code and make it faster. 



