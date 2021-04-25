# Matplotlib-challenge
This challenge uses the Matplotlib and Pandas libraries for Python to manipulate and visualize multiple data sets. The python script is written using jupyter notebooks to easily carry out sequantial operations, and visualize plots as they are being created. 

![code_sample.png](https://github.com/bakerv/Matplotlib-challenge/blob/main/Images/code_sample.PNG)

## Data Set
The Pymaceuticals datasets were utilized for this challenge. These emulate clinical trial data for oncology research. 

One data set contained characteristics for each mouse in the trial, including gender, weight, and drug regimen the mouse was participating in.

![mouse_metadata_sample.png](https://github.com/bakerv/Matplotlib-challenge/blob/main/Images/mouse_metadata_sample.PNG)

The second set contained study data measuring tumor volume and number of metastatic sites over a 45 day period.

![study_results_sample.png](https://github.com/bakerv/Matplotlib-challenge/blob/main/Images/study_results_sample.PNG)

## **Overall Analysis**

Two drugs, Capomulin and Ramicane, show promise as drug treatments. Mice treated with these drugs have far greater survival rate than those treated with a placebo.

![SurvivalRatesStackedBar.png](https://github.com/bakerv/Matplotlib-challenge/blob/main/Images/SurvivalRatesStackedBar.png)

Additionally, both drugs have demonstrated the ability to not only suppress tumor growth, but decrease tumor size. Both drugs had a median tumor volume, for the cohorts as a whole, that was less than the initial tumor volume. Indeed, 75% of mice in these cohorts showed a decrease in tumor size.

![TumorSizeBoxPlot.png](https://github.com/bakerv/Matplotlib-challenge/blob/main/Images/TumorSizeBoxPlot.png)

I recommend the selection of Capomulin and Ramicane for further study. We should employ larger cohorts and evaluate these findings statistically versus a null hypothesis.
### Work Cited:
Inspiration for setting up quantile definitions was taken from codegrepper.com user batman_on_leave