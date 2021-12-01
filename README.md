# Machine_Learning_21_CH
Repository for Machine Learning module in partial fulfillment of HDIP in Computer Science and Data Analytics - GMIT


## Learning outcomes
* Describe the stochastic nature of real-world measurements.
* Select an appropriate mathematical model of a real-world problem.
* Select an appropriate cost function for a given machine learning task.
* Apply an optimisation technique to the parameters of a model


# Scikit-Learn
You can view the Static Jupyter Notebook at the following link: [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/colmhiggs11/Machine_Learning_21_CH/blob/main/Scikit-Learn.ipynb)

You can view the Dynamic Jupyter Notebook at the following link:
[![Binder](https://mybinder.org/badge_logo.svg)]([![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/colmhiggs11/Machine_Learning_21_CH/HEAD))


# Scipy Stats

You can view the Static Jupyter Notebook at the following link: [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/colmhiggs11/Machine_Learning_21_CH/blob/main/Scipy_Stats.ipynb)

You can view the Dynamic Jupyter Notebook at the following link:
[![Binder](https://mybinder.org/badge_logo.svg)]([![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/colmhiggs11/Machine_Learning_21_CH/HEAD))


https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/



## Information
This repository contains the files for the project in the Programming and Scripting module 2020. Key files in this repository include the following files which will be explained in more detail below. *(For quick access to the files just click on them below)*

* [README.md](https://github.com/colmhiggs11/ProandS_Project/blob/master/README.md) *(Description and Analysis of the project)*
* [IRIS.csv](https://github.com/colmhiggs11/ProandS_Project/blob/master/IRIS.csv) *(Data File)*
* [2.analysis.py](https://github.com/colmhiggs11/ProandS_Project/blob/master/2.analysis.py) *(Program/Script to run functions)*
* [iris_functs](https://github.com/colmhiggs11/ProandS_Project/blob/master/iris_functs.py) *(Functions of code created to be called in main **2.analysis.py** file )*
* [Summary.txt](https://github.com/colmhiggs11/ProandS_Project/blob/master/summary.txt) *(Output of summary required for project)*
* [Plots](https://github.com/colmhiggs11/ProandS_Project/tree/master/Plots) *(Folder containing below outputs)* 
    * [Histogram Plots](https://github.com/colmhiggs11/ProandS_Project/tree/master/Plots/Histogram%20PNG's) *(PNG files required for project)*
    * [Scatter Plot](https://github.com/colmhiggs11/ProandS_Project/blob/master/Plots/Scatterplot%20of%20variables.png?raw=true) *(PNG files required for project)*
    * [Violin Plot](https://github.com/colmhiggs11/ProandS_Project/blob/master/Plots/Violin%20plot%20of%20variables.png?raw=true)
    * [Correlation Heatmap](https://github.com/colmhiggs11/ProandS_Project/blob/master/Plots/Correlation%20Heatmap.png?raw=true)

* **Other items**
    * [Project Plan](https://github.com/colmhiggs11/ProandS_Project/tree/master/Project%20Planning) *(Latest revision of the Project Plan - Broken down into sections with completion status)*
    * [Images used in the README.md](https://github.com/colmhiggs11/ProandS_Project/tree/master/Pictures)
    * [License](https://github.com/colmhiggs11/ProandS_Project/blob/master/LICENSE) *(MIT License)*
    * .gitignore


---
## 1.  Introduction
This project is an analysis of the well known Iris dataset for the Introduction to Programming and Scripting module as part fulfilment of the Higher Diploma in Science in Computing (Data Analytics). The project focuses on the widely known Fischer Iris. It requires research and analysis of the dataset and presentation of the findings. The main objective of this analysis is to try and classify the three species of Iris flower by using the four measurements of Sepal width, Sepal length, Petal width and Petal length. The analysis should show if this is possible and will be done in the steps laid out in the README. 

---
### 1.1 README Layout
#### [Background - Data Analysis / Fisher / IRIS data](#2-background-r-fisher--iris-data)
*This section will include a description of how an analysis/investigation of a dataset is completed and a brief introduction into Ronald Fisher and a look at some of his work.*
#### [Code for analysis](#3-Code-for-analysis)
*This section will discuss the code written to complete the analysis. A list of libraries used, instructions on how to run/download the program and details on what the program actually does will also be included.* 
#### [Analysis of Data](#4-analysis-of-data)
*This section will include discussion and analysis of the **outputs** (plots, histograms & summary files)*
#### [Summary / Conclusions](#5-Summary--Conclusions)
*This section will summarise the analysis section and give conclusions based on the data presented.*

## 2. Background R Fisher & Iris Data
### 2.1 Ronald Fisher
Sir Ronald Fisher (1890-1962) was a British statistician and 

<div align="center">

|![Fisher Data Table](https://github.com/colmhiggs11/ProandS_Project/blob/master/Pictures%20for%20README/Fischer%20Data%20Table.PNG?raw=true)|
|:--:| 
| *Fishers Iris Dataset -“The use of multiple measurements in taxonomic problems” (Fisher, 1936)* |

|![Fisher Data Table](https://github.com/colmhiggs11/ProandS_Project/blob/master/Pictures/History.png?raw=true)|
|:--:| 
| *Fishers Iris Dataset -“The use of multiple measurements in taxonomic problems” (Fisher, 1936)* |

<div align="left">

---
### 2.2 Data Analysis
Data analysis is a process of analysing a dataset using 


---
### 2.3 Iris Dataset
The Iris Dataset or 

<div align="center">

|![Iris Flower types](https://github.com/colmhiggs11/ProandS_Project/blob/master/Pictures%20for%20README/Flower%202.png?raw=true)|
|:--:| 
| *Iris flowers by species & measurements included in Fishers Dataset* |

<div align="left">

The dataset used in this analysis was obtained from [UCI archive](https://archive.ics.uci.edu/ml/datasets/iris). There were two errors which required updating the .csv file.
    
    This data differs from the data presented in Fishers article (identified by Steve Chadwick, spchadwick '@' espeedaz.net ).
    The 35th sample should be: 4.9,3.1,1.5,0.2,"Iris-setosa" where the error is in the fourth feature. The 38th sample:
    4.9,3.6,1.4,0.1,"Iris-setosa" where the errors are in the second and third features.


## 3. Code for analysis

### 3.1 How it was written
The analysis of the Iris dataset will be completed
 
---
### 3.2 How to run
To complete the analy

---
### 3.4 What the code does
The two main file that will provide the outputs for the analysis are *[iris_functs.py](https://github.com/colmhiggs11/ProandS_Project/blob/master/iris_functs.py)* and *[2.analysis.py](https://github.com/colmhiggs11/ProandS_Project/blob/master/2.analysis.py)*.

<div align="center">

---
#### iris_functs.py

<div align="left">

---

<div align="center">

---
#### 2.analysis.py
<div align="left">

---
**Importing Functions and list** - The functions created above were imported and the list assigned to variable heading also imported so that both cold be called for execution. (*Shown below*)

    import iris_functs as ifs
    from iris_functs import heading,Data

**Calling functions** - Each of the functions were then called. Some required using the list **"heading"** to be passed through as the argument. (*Shown below*)


## 4. Analysis of Data
### 4.1 Summary.txt
The summary table below shows the output that can be found in the [summary.txt](https://github.com/colmhiggs11/ProandS_Project/blob/master/summary.txt) file using the describe() function that was executed on per species type of Iris flower. The values for each summary metric are discussed below the table.

<div align="center">

  

<div align="left">

---
#### Count
All values clearly show that measurements were taken on 50 flowers in each of the three species.

---
#### Mean
Shows the average measurements taken for each of the flower types. 
|Name | Comment|
|:--|:--|
|Sepal-length:|This is the measurement with the least variation across all of the Iris flowers ranging from 5-6.58 cm for with Setosa being the smallest and Virginica the largest.|


---
#### Standard Deviation (Std)

<div align="center">

|![Standard deviation table](https://github.com/colmhiggs11/ProandS_Project/blob/master/Pictures/Standard%20Deviation.png?raw=true)|![Probability Density formula](https://github.com/colmhiggs11/ProandS_Project/blob/master/Pictures/Probability%20Density.PNG?raw=true)|
|:--:|:--:|
| *Empirical rule distribution*  | *Probability Density formula* |


<div align="left">


<div align="center">

*Standard deviation by measurement variable*


Name | Comment
:--------------|:--
|Sepal-length:|In terms of sepal length 99.7% of the data for each of the flowers fall into the following ranges: **Setosa: 3.9 



---
### 4.2 Histograms

|![hist](https://github.com/colmhiggs11/ProandS_Project/blob/master/Plots/Histogram%20PNG's/sepal-length.png?raw=true)|![hist](https://github.com/colmhiggs11/ProandS_Project/blob/master/Plots/Histogram%20PNG's/sepal-width.png?raw=true)|
|:--:|:--:|
| *Sepal Length per Species* |*Sepal Width per Species*|

|![hist](https://github.com/colmhiggs11/ProandS_Project/blob/master/Plots/Histogram%20PNG's/petal-length.png?raw=true)|![hist](https://github.com/colmhiggs11/ProandS_Project/blob/master/Plots/Histogram%20PNG's/petal-width.png?raw=true)|
|:--:|:--:|
| *Petal Length per Species* |*Petal Width per Species*|

---
### 4.3 Scatterplots


---
### 4.4 Violin Plots

|![Violin Plot of four measurements per species](https://github.com/colmhiggs11/ProandS_Project/blob/master/Plots/Violin%20plot%20of%20variables.png?raw=true)
|:--:|
| *Violinplot of four measurement variables per species* |




<div align="left">

---
### 4.5 Correlations

|![Heatmap](https://github.com/colmhiggs11/ProandS_Project/blob/master/Plots/Correlation%20Heatmap.png?raw=true)
|:--:|
| *Overall correlation between measurment variables in Iris Dataset* |


<div align="left">

## 5. Summary / Conclusions
Taking all of the data into account it is clear to see that the setosa flower is linearly separable from the virginica and versicolor flowers. To differentiate between the two latter flowers takes a lot more time and research has shown that with Machine learning programs the probability of being able to determine which species you are dealing with can be completed with a relatively high degree of accuracy. Setosa flowers have a much smaller petal width and petal length than the other two, and while their sepal length is on the smaller side but similar to that of Virginicas and Versicolors, Setosa's sepal width is typically  larger than its rival species. To differentiate between Virginica's and Versicolors you need to look at data and relationships side by side. Although Virginica's typically have a larger petal length and petal width, there is more of a correlation between those two when looking at Versicolors.

## 6. Licence
This project was completed using the [MIT License](https://opensource.org/licenses/MIT). Due to the limited restrictions it puts on reuse, it has a high license compatibility.

## 7. References


