# IBEX35 Investment Strategies for post-COVID European Outbreak

The aim of this project (in addition to practising programming and data analysis) is to empirically compare two investment strategies to ascertain if the stock market is efficient in the short-term. The sampling frame for the study is the components of the index IBEX 35. The method is secondary data analysis, concretely adjusted close price from Yahoo Finance. I wrote the code for the analysis in the programming language Python.


**Hypothesis: Should the stock market be efficient in the short-term, investors would allocate their resources efficiently throughout the first weeks of the European COVID outbreak. Thereby shares with higher returns would forecast (or indicate) those businesses less vulnerable to the virus.**

As from 19 February, financial markets began to price in the possible effects of a pandemic over businesses functioning. This date sets the start of the time interval to analyse. The end of the period to study must also be relevant; thus I selected 19 March, when the European Central Bank announced its emergency plan response to the virus. Therefore the period to conduct the data analysis is from 19 February to 19 March.

If the hypothesis was correct, an investment portfolio composed of the equities with higher returns over the aforementioned period will perform well for the post-COVID outbreak development phase. Hence the goal of the data analysis (**1_ibex_data_analysis.ipynb**) is to find out those stocks, for then simulate and track, from 19 March onwards, what I named “Short Term Efficient Portfolio”.

I built a second portfolio for comparison purposes. The analysed sample is the same, albeit from March 2009 to February 2020 (before European COVID outbreak). The approach was different: instead of selecting stocks based on their total return throughout the analysed period, I used optimisation (Sequential Least Squares Programming method due to its accuracy in financial time series analysis), seeking to maximise expected return and minimise volatility, to figure out the stocks and weights of an optimal portfolio (**1_ibex_data_analysis.ipynb**): “Optimised Portfolio 2009-2020”. 

The simulation of these investment portfolios, both from 19 March 2020 (date when I wrote the code) onwards, is being conducted on investing.com and their performance is included in **2_portfolio_total_return.ipynb** (last update at the stock exchange closing time on 17 July 2020).
