# DS200:Research Methods
* * *
## Module 4 : Assignment
* * *

> **Aim of this assignment is to explore one of datasets in data.gov.in and plot in matplotlib**

### Part1: - Dataset
> The dataset is <a href="#my_anchor">[1]</a> **Primary Energy Consumption in Select Countries of the World from 2012 to 2018** and is  downloaded from [here](https://data.gov.in/resources/primary-energy-consumption-in-select-countries-of-the-world-from-2012-).
>> The data is released under ** National Data Sharing and Accessibility Policy (NDSAP)** 

### Files
1.  There are folders named as 'data' and 'plots' inside ZIP file. Along with these, python script, 'DS200Plots.py' is also there.
2.  'data' folder contains the data file, 'primaryEnergy.xls'. And all the plots are saved in 'plots' folder
3.  Along with these, I am also uploading the jupyter notebook, 'DS200Plots.ipynb'  

### Part2: - Scatter Plot

![scatterplot](plots/scatterPlot.png)

1.  The plot on left has **Number of complaints registered suomoto by police** -i.e The cases registered by police based on their investigation - vs **Number of complaints registered as SLL** (SLL:- Special and Local Laws, these are laws which are not part of IPC and include law instituted by Acts like Gambling Act 1867, Forest Act 1927, etc) for 28 states (based on 2009 data) and 7 union territories of India.
2.  The plot on the right has **Number of complaints registered to police by oral,written or via helpline** vs **Number of cases registered as SLL**  for 28 states (based on 2009 data) and 7 union territories of India.
3.  Both the **x-axis** and **y-axis** are on log10 scale. Best fit line is also plotted in each scatter plot.
4.  **r** denotes the correlation coefficient between the data on **x-axis** and **y-axis**. 
#### The observations one can derive from the scatterplot are the following:-
1.  The number of complaints registered suomoto by the police for a state/UT are highly correlated with the number of complaints filed under SLL. 
2.  The correlation between number of complaints registered by others(not suomoto by police) are not correlated to the number of complaints filed under SLL to that extent.
3.  The regression line in plot (a) fits the data better than in plot (b).   
4.  A logical reason for this is that mostly complaints under Special and Local Laws are filed againsts an entity after investigation by law enforcers and are therefore not filed on recieving of first complaint (with few exceptions like cognizible crime under Dowry Actor SC/ST attrocity ACT).

* * *

### Part2: - Box Plot
> Below are two boxplots.
![scatterplot](plots/BoxPlot_log.png)
![scatterplot](plots/scatterPlot_linear.png)

1.  The plot on the left shows the box plot of **Number of complaints received by police** in two catergories. First the complaints which are submitted to police by other entities via oral,written means or using police helpline for all 35 states and U.Ts. Second are the complaints that are registered by police suomoto for all 35 states and U.Ts. The first boxplot shows the number of complaints on log scale along with the outliers.
2. The second boxplot shows the same data as (1) but on a linear scale without outliers.
#### The observations one can derive from the boxplots are the following:-
1.  Looking at (b) we can say that on an average more complaints are registered by outside entities than suomoto by law enforceres.
2.  The spread in number of complaints filed by non law enforcers is more. This category also has less outliers than the other.
3.  The complaints registered suomoto by law enforcers are very high compared to the IQR in a few States/UTs and hence have more outliers.


* * *
### Part3: - Bar Chart
> Below is the Barchart which shows for all States and U.Ts (those that existed in 2009) how many complaints are filed by non law enforcers and suomoto by police.

![lineplot](plots/lineplot.png)

1.  The Bar chart shows on log10 scale the **number of complaints**. The **blue** bar denoted the **number of complaints  received by police via oral/written/helpline** and the **red** bar denoted the **number of complaints filed suomoto by police** for all 35 states and U.Ts .

#### The observations one can derive from the bar chart are the following:-

1.  Apart from T.N, Goa, U.P, A&N Islands and Uttarakhand in all states more complaints are recieved via oral/written/helpline means. This explains the higher average of number of complaints received via oral/written/helpline means in box plot.
2.  Although in most of states the number of suomoto complaints are considerably less than the other category, in some of them the number is closer or even higher than later. This explains the reason for high number of outliers.


## References
<b id="my_anchor">[1].</b> Primary Energy Consumption in Select Countries of the World from 2012 to 2018, [https://data.gov.in/resources/primary-energy-consumption-in-select-countries-of-the-world-from-2012-](https://data.gov.in/resources/primary-energy-consumption-in-select-countries-of-the-world-from-2012-).


