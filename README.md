<div id="top"></div>

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/colmhiggs11/Machine_Learning_21_CH">
  
  </a>

<h1 align="center">SciKit Learn & SciPy analysis </h1>

  <img alt="SciKit" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Scikit_learn_logo_small.svg/1200px-Scikit_learn_logo_small.svg.png" width="25%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="SciPy" src="https://nlaongtup.github.io/post/scipy-lammps/featured.png" width="25%">
</p>

<p align="center">
     Machine Learning and Statistics project to analyse SciKit Learn and SciPy stats by looking at the built in algorithms and using example dataseets,plots & visualisations  
    <br />
    <a href="https://github.com/colmhiggs11/Machine_Learning_21_CH"><strong>Explore the docs in Repository »</strong></a>
    <br />

</div>



<!-- TABLE OF CONTENTS -->
## Table Of Contents

1. <a href="#1-about-the-project">About The Project</a>
    - <a href="#project-description">Project Description</a>
    - <a href="#in-this-repository">In this repository</a>
2. <a href="#2-getting-started">Getting Started</a>
    - <a href="#prerequisites">Prerequisites</a>
    - <a href="#installation">Installation</a>
3. <a href="#3-scikit-learn">Scikit Learn</a>
4. <a href="#4-scipy-stats">SciPy Stats</a>
5. <a href="#5-conclusions">Conclusions</a>
6. <a href="#6-license">License</a>

<!-- ABOUT THE PROJECT -->
## 1. About The Project

### Project Description
- Scikit - Learn
    - A clear and concise overview of the scikit-learn Python library. 
    - Demonstrations of three interesting scikit-learn algorithms.
- Scipy Stats
    - A clear and concise overview of the scipy.stats. 
    - An example hypothesis test using ANOVA. Find a data set on which it is appropriate to use ANOVA, ensure the assumptions underlying ANOVA are met, and then perform and display the results of your ANOVA using scipy.stats.

<p align="right">(<a href="#top">back to top</a>)</p>

### In this repository

* [README.md](https://github.com/colmhiggs11/Machine_Learning_21_CH#readme) *(Layout and details of the project)*
* [Scikit-Learn.ipynb](https://github.com/colmhiggs11/Machine_Learning_21_CH/blob/main/Scikit-Learn.ipynb) *(Scikit Learn Jupyter Notebook)*

* [Scipy_Stats.ipynb](https://github.com/colmhiggs11/Machine_Learning_21_CH/blob/main/Scipy_Stats.ipynb)  *(Scipy Stats Jupyter Notebook)*


**Other items**
* [Data](https://github.com/colmhiggs11/Machine_Learning_21_CH/tree/main/Data)
    * __SciKit Learn__
    * [MC.csv](https://github.com/colmhiggs11/Machine_Learning_21_CH/blob/main/Data/MC.csv) *(Data File for the analysis of KNN algorithm)*
    * [data.csv](https://github.com/colmhiggs11/Machine_Learning_21_CH/blob/main/Data/data.csv) *(Data file for analysis in Scikit Learn)*
    * __SciPy Stats__
    * [StudentPerformance.csv](https://github.com/colmhiggs11/Machine_Learning_21_CH/blob/main/Data/StudentPerformance.csv) *(Data File for ANOVA analysis)*

* [Images used](https://github.com/colmhiggs11/Machine_Learning_21_CH/tree/main/Images)
* [License](https://github.com/colmhiggs11/Machine_Learning_21_CH/blob/main/LICENSE) *(MIT License)*    
* [Requirments.txt](https://github.com/colmhiggs11/Machine_Learning_21_CH/blob/main/Requirements.txt)
* .gitignore
<p align="right">(<a href="#top">back to top</a>)</p>

***

<!-- GETTING STARTED -->
## 2. Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### **Prerequisites**

The libraries and packages that need to be installed for running this code are shown in requirements.txt, you will also need to either have access to anaconda/python in another form to work on the actual file, access to a web browser where you can work on your own copy of the version using binder. This will not update/save the notebook unless you copy the code down. You can also look at a rendered view of the notebook by clicking the badges in the follwoing links. [Scikit-Learn.ipynb](https://github.com/colmhiggs11/Machine_Learning_21_CH/blob/main/Scikit-Learn.ipynb) , [Scipy_Stats.ipynb](https://github.com/colmhiggs11/Machine_Learning_21_CH/blob/main/Scipy_Stats.ipynb).


### **Installation**

1. If you have anaconda installed, go to the command line and complete step 2.
2. Clone the repo
   ```sh
   git clone https://github.com/colmhiggs11/Machine_Learning_21_CH.git
   ```
3. Open Jupyter lab
   ```sh
   jupyter lab
   ```
4. This will open the Jupyter Notebookin the browser. From here ensure all of the items in the requirments.txt file are installed. If any of them are missing or need to be updated use the following command.
   ```sh
   pip install-r requirements.txt 
   ```

<p align="right">(<a href="#top">back to top</a>)</p>

---

## 3. Scikit Learn
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/colmhiggs11/Machine_Learning_21_CH/blob/main/Scikit-Learn.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/colmhiggs11/Machine_Learning_21_CH/HEAD)




The Scikit-Learn notebook as mentioned above can be cloned and opened up through Jupyter Lab & python users. For users that do not have access to python/jupyter lab a rendered view can be found by clicking on the nbviewer badge. A rendered version can be access and launched by clicking on the binder badge and selecting the SciKit Learn jupyter notebook. This notebook analyses the SciKit learn and three algorithms that are used in machine learning. We follow the steps lined out in the machine learning process flow below.

<div align="center">

<img alt="SciKit" src="https://github.com/colmhiggs11/Machine_Learning_21_CH/blob/main/Images/MLProcess.jpg?raw=true" width="50%">

<div align="left">
We run through the steps and end up with a confusion matrix and accuracy score for the models as shown below. We try to optimise the models using the Hyperparameters associated with each of the algorithms. 

<div align="center">

<img alt="SciKit code" src="https://github.com/colmhiggs11/Machine_Learning_21_CH/blob/main/Images/Readme.png?raw=true" width="50%">

<div align="left">


---
## 4. Scipy Stats

 [![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/colmhiggs11/Machine_Learning_21_CH/blob/main/Scipy_Stats.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/colmhiggs11/Machine_Learning_21_CH/HEAD)

The SciPy Stats notebook as mentioned above can be cloned and opened up through Jupyter Lab & python users. For users that do not have access to python/jupyter lab a rendered view can be found by clicking on the nbviewer badge. A version can be access and launched by clicking on the binder badge and selecting the Scipy Stats jupyter notebook. This notebook analyses the SciPy stats module focusing mainly on the ANOVA statistical test. The test follows the assumptions below and the data must pass each of the assumptions to complete the ANOVA f_oneway otherwise it will take a different path which is the Welch's ANOVA.  

<div align="center">

<img alt="SciPy Assumptions" src="https://github.com/colmhiggs11/Machine_Learning_21_CH/blob/main/Images/ANOVA.png?raw=true" width="50%">

<div align="left">

The p-value determines whether most of the assumptions are passed. Typically this decision is based off whether the value is above or below 0.05.

The idea behind the ANOVA test is to see whether the categories are significantly different to each other in terms of the mean values.

---

## 5. Conclusions
It is clear why SciKit learn is one of the most frequently used machine learning libraries. In a short number of lines of code the user can make predictions on almost any dataset assuming they have done the prerequisites of data processing, chossing what algorithm best fits the data and tuning hyperparameters. The more data that the machine learning model sees allows it to be constantly updating its training database and perform even more accuratley. 

SciPy stats is very useful in completing statistical analysis of datasets and comparing them to see if there is a significant distance between them. The correlations between these datasets can prove useful when performing subsequent analysis. 

---

## 6. License
This project was completed using the [MIT License](https://opensource.org/licenses/MIT). Due to the limited restrictions it puts on reuse, it has a high license compatibility.

<!-- MARKDOWN LINKS & IMAGES -->
<!-- <https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/colmhiggs11/Machine_Learning_21_CH.svg?style=for-the-badge
[contributors-url]: https://github.com/colmhiggs11/Machine_Learning_21_CH/graphs/contributors
[issues-shield]: https://img.shields.io/github/issues/colmhiggs11/Machine_Learning_21_CH.svg?style=for-the-badge
[issues-url]: https://github.com/colmhiggs11/Machine_Learning_21_CH/issues
[license-shield]: https://img.shields.io/github/license/colmhiggs11/Machine_Learning_21_CH.svg?style=for-the-badge
[license-url]: https://github.com/colmhiggs11/Machine_Learning_21_CH/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=006
[linkedin-url]: https://linkedin.com/in/colm-higgins-3a776711b
[product-screenshot]: images/screenshot.png