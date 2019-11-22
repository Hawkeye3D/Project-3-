# Project  Three - Net Electrical Energy Projection and CO2 Analysis for the United States from 2019 to 2050, a back-of-the-envelope estimation using EIA data.

![1574437920625](C:\Users\kevin\AppData\Roaming\Typora\typora-user-images\1574437920625.png)

MOBIUS ENERGY GROUP :

Preethi Dayanand, Wyatt Carnes, Russell Haws, Kevin McClard

This project is designed to deliver a basic analysis of the current net electrical utilization in the US, primary sources of energy used to generate that electricity, and to focus on the trends of wind and solar renewables to estimate how much influence they will have by the year 2050.  The study begins with a quick observation of where we are currently.  It is followed by a quick analysis of a leader in renewables, Sweden; the purpose of which is to illustrate the scale of the American energy scene.  

The software tools used to do this analysis are Python, utilizing numerous libraries, the most significant of which is the Statmodel.  We utilized a subclass of Statmodel, TSA or Time Series Analysis, to create a linear projection which incorporates seasonal variations observed from historical data.  This technique implements a set of advanced filters and a machine learning algorithm; it is quite sophisticated.  Three energy projections are illustrated, the first being the current trend.  Next, a linear projection in which all the seasonal variations are varied by 5% is done, and last a compounded 7% model projection is illustrated.  The presentation will discuss the observations of these projections.  These projections are followed by a financial analysis of companies that are involved in green energy.

Lastly, Tableau is used to illustrate the CO2 footprint of the United States by county and how this map can be used to help identify problem areas, and areas that have no data being reported.  

The website is:https://projectthreehometeam.bss.design/politics.html
