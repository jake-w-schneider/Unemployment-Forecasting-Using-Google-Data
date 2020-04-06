# The Coronavirus Contraction May Be More Severe Than the Great Depression <br>
*The March U.S. Unemployment Rate of 4.4% is Not Capturing Current Conditions. The Real Rate is Likely Closer to 14.1%, with April Heading Even Higher.* <br>
<br>
Jake Schneider <br>
Monday, April 6, 2020 <br>
<br>
---
![alt text](https://github.com/jschneids13/Unemployment-Forecasting-Using-Google-Data/blob/master/Unemployment%20Rate%20Using%20Google%20Trends.png)
*Instead of the 4.4% rate reported by the BLS, U.S. unemployment in March might actually be closer to 14.1%.* <br>
<br>
<br>
Last Friday, the Bureau of Labor Statistics reported their monthly Employment Situation in which they stated that the U.S. national unemployment rate for March was 4.4%. This number is misleading, and in fact, the true unemployment rate at the end of March may be much closer to 14.1%. Using a combination of both official economic data from the U.S. government and real-time estimates from Google internet searches, we believe April unemployment could reach as high as 35.8%. If true, the likely Coronavirus contraction could be even more severe than the Great Depression. <br>
<br>
Many venerable economists have lauded the ability of unconventional indicators, such as internet queries, to forecast future economic conditions. In fact, in a 2009 paper Google Chief Economist Hal Varian and Data Scientist Hyunyoung Choi demonstrated that the Google searches could be used to accurately predict official unemployment insurance claims. As opposed to using an Autoregressive Model as the previous authors employed in their article, our team created a simpler model that merely regressed Google searches for the term "unemployment benefits" against the unemployment rate. As demonstrated in the figure above, the predicted unemployment rate (as demonstrated by the red dotted line), even if simply constructed, does an adequate job of modeling the actual unemployment rate going back to 2004, including during the Great Recession.[1] <br>
<br>
The results of the analysis are startling. As opposed to the currently reported statistic of 4.4% from the Bureau of Labor Statistics (BLS), our results suggest that March's unemployment rate is in fact closer to 14.1%. One might question how the March official numbers could be so different from our prediction? The answer is, to construct the unemployment rate, the BLS surveys a select group of households during the second week of the month. For the month in question, this survey was conducted between March 8 and March 14, well before the widespread use of 'social distancing', business closures and mass layoffs. Therefore, the current statistic of 4.4% is based upon a figure from early in the spread of the Coronavirus and does not yet truly reflect its impacts on the U.S. economy.
Although grim, this is not even the bad news. Based on these same google searches for 'unemployment benefits' during the beginning days of the month of April, these queries reached their highest levels ever by a factor 3 and are 5 times higher than they ever were during the Great Recession. The underlying search data from Google Trends is in the figure below. <br>
<br>
![alt text](https://github.com/jschneids13/Unemployment-Forecasting-Using-Google-Data/blob/master/Google%20Trends%20for%20Unemployment%20Benefits.png)
*Current searches for the term 'Unemployment Benefits' is 5 times higher than during the peak of the Great Recession.* <br>
<br>
Ultimately, our analysis suggest that the April unemployment rate could be the highest on record, and even as high as 35.8%. Even during the Great Depression, when unemployment peaked at 24.9% in 1933, the labor market did not deteriorate so quickly. If Google Trends data is harbinger of future unemployment rates, then this contraction might be the most severe ever.
<br>
<br>
# *About the Author*
Jake W. Schneider is the President & Founder of Schneider Economics, LLC, a bespoke economic research firm that uses the intersection of tried-and-true analytics with up-and-coming data science techniques. Mr. Schneider is a Master in Public Administration in International Development candidate at the Harvard Kennedy School (2020) where he concentrates on the intersection of economics, data science and public policy. Previously, Mr. Schneider has served as a consultant for the Multilateral Investment Guarantee Agency (MIGA) at the World Bank, a researcher at The Brookings Institution and an analyst reporting directly to former Federal Reserve Chairman Dr. Alan Greenspan at Greenspan Associates, LLC. Mr. Schneider holds a B.A. in economics magna cum laude with honors from The College of William & Mary in Virginia. 
<br>
He can be contacted at jake.schneider@schneidereconomics.com.
<br>
# *Medium Article*
The article can be read in its orginal publication here:
https://medium.com/@jschneids13/the-coronavirus-contraction-may-be-more-severe-than-the-great-depression-8e31f5196f2
# *Special Thanks*
The author would like to thank Peter McKelvey, President Emeritus of L.E.K. Consulting, and Jon Hartley, Senior Policy Advisory for the U.S. Congress Joint Economic Committee, for their helpful comments and suggestions.
<br>
# *Bibliography*
Bureau of Labor Statistics. 2020. The Employment Situation - March 2020. April 3. Accessed April 4, 2020. https://www.bls.gov/news.release/pdf/empsit.pdf. <br>
Varian, Hal, and Hyunyoung Choi. July 5, 2009. "Predicting Initial Claims for Unemployment Benefits." <br>
<br>
# *Notes*
[1] Despite its simplicity, the results of our bivariate regression are compelling with an R2 of 49.7%, an Adjusted R2 of 49.5% and a t-statistic on the variable of interest of 13.8. We make no causal claims and thus controlling for confounding variables or adopting an econometric research design was unnecessary. For robustness, we also regressed the term "Unemployment Insurance" on the official unemployment rate and found similar results. We did not utilize an Autoregressive (AR) or ARIMA model in order to maintain simplicity and ease of understanding for the general reader. All analyses are available on the author's GitHub page here: https://github.com/jschneids13/Unemployment-Forecasting-Using-Google-Data.
