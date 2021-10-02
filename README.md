## Exploring MatplotLib plotting utilities
This project was part of module 4 of research methods course at CDS, IISc. The aim is to explore basic plotting utilities of matplotlib library.
### Software used
- python3.7, jupyter notebook, pandas, matplotlib libraries, git 
### Data source and summary
- I explored publicly available food grain production dataset from https://data.gov.in 
- Specifically, the following link gives distribution of crop produce in Inida. - https://data.gov.in/resources/stateut-and-crop-wise-production-foodgrains-2016-17-2019-20-ministry-agriculture-and.
- This dataset gives crop-wise and total food produced in kilotones across different states of India over the period 2016-2020
- Note: Data corresponding to seasons 2018-2019 and 2019-2020 are incomplete, hence I utilized 2016-2017 and 2017-2018 seasons
### Plots to be generated
- Scatter plot, box plot and bar plot
- Notebook : https://github.com/hariharanrav/Module4_ResearchMethods/blob/master/MatplotLib.ipynb

### Hypothesis 1 : Is their correlation between food grain production over two years across different states?
-  By scatter plotting total production of season 2016-2017 against 2017-2018, the above hypothesis can be verified.
-  Expected positive correlation with slope tilting towards y-axis demonstrating increase in produce over years. 
### Scatter plot
- Inferences : Trend over years is largely increasing, as seen below
- Few states have increase production more compared to other states, which means they will deviate from the trend more. E.g. TamilNadu
- Few states have decreased capacity and they fall below the trend
<img src="https://github.com/hariharanrav/Module4_ResearchMethods/blob/master/ScatterPlot.png" width="600" height="600">

### Hypothesis 2 : Is the food grain production increasing over the years?
### Box plot
- By box plotting production values across two seasons, one understand how distribution is evolving
- As the plot below shows, the min, mean and maximum have shifted from 2016-2017 to 2017-2018. Hence there is a clear uptrend in production
 <img src="https://github.com/hariharanrav/Module4_ResearchMethods/blob/master/BoxPlot.png" width="500" height="500">
 
### Hypothesis 3: How is the production changing over seasons for each state?
### Grouped bar plot
- By plotting production amounts for two seasons grouped by state/UT names, relative change in production for each state can be ascertained. 
- As seen below, few states like Tamil Nadu have increased the food grain production ove the two seasons while few other states have seen a decrease in produciton.
<img src="https://github.com/hariharanrav/Module4_ResearchMethods/blob/master/BarPlot.png" width="600" height="600">

