![](https://img.shields.io/badge/Python-3.0-green.svg)
![](https://img.shields.io/badge/Data-Visualization-orange.svg)
![](https://img.shields.io/badge/Status-Completed-brightgreen.svg)

# Exploratory Data Analysis

## *Exploratory Data Analysis refers to the critical process of performing initial investigations on data so as to discover patterns,to spot anomalies,to test hypothesis and to check assumptions with the help of summary statistics and graphical representations.*

### About the data set - 
**Iris** dataset contains four different features, those are- 
* Petal Length
* Petal Width
* Sepal Length
* Sepal Width  

Depending on the above 4 features, a plant will be categorized and placed in  5th column is derived, i.e., "Species". And they are - 
* Setosa
* Versicolor 
* Virginica
### Aim - 
#### ***To distinguish an unknown flower into one of the three category of species***


### Packages used - 
*Multiple packages were used* in the notenook. These packages were imported into python 3 version. The packages are:
* Numpy
* Pandas
* Seaborn
* Matplotlib

The first two packages are for combutation and data analysis, and the other two package are for data visulaization. However, Machine learning is covered in other notebook.


## Data Visualization
We now have a basic idea about the data. We need to extend that with some visualizations.
We are going to look at two types of plots:

- ***Univariate plots*** to better understand each attribute, without dealing with causes or relationship.
    * 1-D scatter plot 
    * Histogram
    * Probability Density Function(PDF) and Cumulative Distribution Function (CDF)
    * Box plot
    * Violin plot
    * Swarm plot
 
 
- ***Multivariate plots*** to better understand the relationships between attributes.
    * Scatter plot
    * Pair plot
    
### Observations and conclusions  -

* By using petal length, we can seperate Setosa.
* In Petal width, Setosa is not properly distrubuted.
* Remaining Sepal length and width, we can't do anything as whole data is messed up and we cannot seperate them.
* So we can choose petal length's data distrubution for analysis.

Therefore, for analysing the data, the below feature can be preferred.  
***PL > PW >> SL >> SW***  
