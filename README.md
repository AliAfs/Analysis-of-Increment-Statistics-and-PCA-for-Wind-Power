# AP1 - Analysis of Increment Statistics and PCA for Wind Power 
## (still ongoing...)

## Introduction:
It is anticipated that significantly more renewable energy sources would be deployed as a result of a rising demand for energy services and attention to environmental issues. Due to decades of scientific discovery and technological advancement, wind energy is already becoming a common source of electricity. According to the WindEurope, 116 GW of new wind farms will be installed in Europe between 2022 and 2026 [1]. Moreover, Germany will have the largest wind market in Europe as a result of its strong expected onshore market's performance over the next five years (19.7 GW) and growing offshore installations (5.4 GW) [1].
<br>The renewable sources, such as wind, are highly fluctuating across different time scale which could greatly influence the power generated from these sources [2].  This intermittent behavior could significantly affect the power system operation. In order to have a stable supply grid based on renewable energies and reduce the reserved capacity, deep understanding of random character of wind and the ability to predict the wind velocity and generated power are needed [3]. 
<br>Different studies has been done on wind time series forecasting. The presented methods can be classified based on their methodology [4]. First, the physical approach that use weather features, such as temperature and pressure, to achieve highest prediction accuracy. The second is the statistical approach, like ARMA model, that is based on the numerus historical data and disregards weather conditions.  Moreover, in many forecasting methods, both physical and statistical models are utilize. In hybrid approach uses weather forecasts and time series analysis simultaneously.  


### Outline
In this project, I am going to inverstigate wind tourbines data from different wind farms in United States. The data is
provided by National Renewable Energy Laboratory (NREL).
<br>The project contains data visualization, data analysis, and prediction on wind velocity and output power time series.
<br><b>1- Data Visualization:</b> Time Series Plot, Heat Maps
<br><b>2- Data Analysis:</b> 
<br><b>a)</b> Histogram and pdf of wind velocity and power
<br><b>b)</b> Scatter Plots. Correlation Matrix. Implementing PCA and finding Emprical Orthogonal Function(eofs).
<br><b>3- Statistical Model/Forcast</b>

[1] WindEurope, “Wind energy in Europe: 2021 Statistics and outlook for 2022-2026, https://windeurope.org/intelligence-platform/product/wind-energy-in-europe-2021-statistics-and-the-outlook-for-2022-2026/#findings, Access date: June 30, 2022
<br>[2] Milan, P., Wächter, M. & Peinke, J. Turbulent character of wind energy. Physical Review Letters 110, (2013).
Data Source: https://odysseus.informatik.uni-oldenburg.de/download/Data/NREL/2006/
<br>[3] Lei, M., Shiyan, L., Chuanwen, J., Hongling, L. & Yan, Z. A review on the forecasting of wind speed and generated power. Renewable and Sustainable Energy Reviews 13, 915–920 (2009).
<br>[4] Wang, X., Guo, P. & Huang, X. A review of wind power forecasting models. in Energy Procedia 12, 770–778 (Elsevier Ltd, 2011).

