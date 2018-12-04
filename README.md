# Investigate and explain box plots and their uses
This assignment has been completed in accordance with the tasks set out in the coursework of the Fundamentals of Data Analysis module as part of the Higher Diploma in Data Analytics in Galway-Mayo Institute of Technology.

## Assignment completed by:
Declan Reidy - December 2018

## Instructions

In order to complete this assigment it was necessary to:
1. Download & install Anaconda
2. Download & install Console Emulator x64
3. Create directory and files such as this README, LICENSE and .gitignore using Linux commands
4. Launch a jupyter notebook from the command line and create FDA-Project.ipynb
5. Download the Anscombe Quartet dataset and read the dataset into FDA-Project.ipynb and perform analysis
6. Sync files on my local machine to repository on GitHub allow me to push/pull updates to the jupyter notebook over various commits


To review the analysis methods and conclusions from the assigment:
1. Simply launch the Jupyter Notebook entitled "FDA-Project.ipynb"
2. Review the full analysis in the Jupyter Notebook
3. Run individual elements of the python code by highlighting cells and using command SHIFT+ENTER
4. Consult the "Objectives" section of this README file for information on the objectives and structure of this assignment
5. Consult the "Initial Research" section of this README file for information on my approach to this assignment
6. Consult the "Method" section of this README file for information on my methodology for this assignment
7. Consult the "References & Research" section of this README file for information on my further reading in relation to this assigment

## Objectives

The aim of this project is to:

Summarise the history of the box plot
Highlight situations in which it is used.
Demonstrate the use of box plots using data.
Explain relevant terminology used in the creation and analysis of box plots including:
{quartile, percentile, median, min, max, outlier, whisker, hinge and fence}
Compare box plotting to some alternatives

## Initial Research

## Method

## References & Research
http://vita.had.co.nz/papers/boxplots.pdf
The box plot is 40 years old. John Tukey formally published in 1977 but introduced it in 1970. It is a compact distributional summary with less detail than a histogram of kernal density. It also takes up less space and is an elegant yet practical way to compare distributions across groups. Tukey called box plots schematic plots.

Five box plot components:
1. The median
2. Two hinges (upper and lower quartiles)
3. Data values adjacent to inner and outer fences (1.5 and 3 times the inter-quartile range from median)
4. Two whiskers that connect the upper and lower hinges to the inner fences (also known as extremes)
5. Potential outliers, individual points further away from the median than the upper or lower extremes.

Problems with box plots:
There is visual display of group size and no way to discern if the differences are significant.
1. Variable width (width varies according to number of points in the group)
2. Notched box plots (adds confidence intervals - the notches)

http://www.physics.csbsju.edu/stats/box2.html
Description of box plot is first to third quartile as the box, maximum and minimum as well as median. Inter-quartile range IQR is Q3-Q1

1. Outliers are either 3×IQR (outer fence) or more above the third quartile or 3×IQR or more below the first quartile.
2. Suspected outliers are slightly more central versions of outliers: either 1.5×IQR or more above the third quartile or 1.5×IQR (inner fence) or more below the first quartile.

Normal distribution IQR = 1.35 * STDEV


http://asq.org/learn-about-quality/data-collection-analysis-tools/overview/box-whisker-plot.html
Box and whisker plots easy to read. Summarize data from multiple sources and display the results in a single graph. These plots allow for comparison of data from different categories for easier, more effective decision-making. Useful for multiple data sets from independent sources that are related to each other.


https://www.khanacademy.org/math/statistics-probability/summarizing-quantitative-data/box-whisker-plots/a/box-plot-review
Simple examples of box plots. Using simple data.
[25], 28, {29, 29}, (30, 34), {35, 35}, 37, [38]
1. Median (30, 34)
2. First Quartile {29, 29}
3. Third Quartile {35, 35}
4. Min [25]
5. Max [38]

https://www.nature.com/articles/nmeth.2813
Histograms require about 30 data points whereas box plots need only 5. More data is given about tails of distribution. Quartiles are insensitive to outliers and preserve information about the centre and the spread. Consequently better than mean and STDEV for population distributions that are asymmetric or irregularly shaped or samples with extreme outliers. Mean could be far from the bulk of the data and thus conventional rules for calculating variance and STDEV may not apply.

Tukey style - Whisker is most extreme data point within 1.5 IQR
Spear style - Whisker is maximum or minimum of the data values

https://flowingdata.com/2011/12/06/40-years-of-boxplots/

Mary Eleanor Spear.

https://www.mathsisfun.com/data/quartiles.html

Quartiles explained simply.
