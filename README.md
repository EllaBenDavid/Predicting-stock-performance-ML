# Predicting-stock-performance-ML
The project deals with stock performance forecasting.
We address 2 research questions.
Classification:
Given a 10K form of a company can it be predicted whether its stock value will rise or fall 
in the following year based on financial indicators only?

Linear regression
2. Given a 10K form of a company in a given year is it possible to predict the rate of change in stock value 
in the following year based on financial indicators only?

The data is based on K10 forms. These forms include a detailed balance sheet, profit and loss statement
and a description of activities during the year. 
In addition, indices calculated on the basis of the reports are attached to the form, such as debt ratio, increase in profits, etc.
The form issued by the companies listed on the american Stock Exchange is submitted to the securities authority in the first quarter of the following year. 
In our data, columns were added to calculate an increase in the value of the stock. A [%] PRICE VAR column that lists the percentage change in the price 
of each share per year. From the first trading day in January to the last trading day in December of that year and whether it went up or down. 
This data is built by the data taken from a web interface called API Prep Modeling Financial which is basically a free interface of historical financial statements 
and stock prices.
The data: 5 CSV files from 2014 to 2018
▪ Each of the files has 226 columns (features) and about 4000 records / examples.
▪ Each record represents one share and the company's financial data for that year.
We worked on the data in 3 steps: consolidating the files, filtering and clearing the data and filling in values.
During the project we used supervised algorithms of linear and logarithmic regression and classification. 
We also used a variety of evaluation methods. 
We got the best results in the Random Forest model.

Link to the project website: http://proj.ruppin.ac.il/gallery/#/ruc21p13

