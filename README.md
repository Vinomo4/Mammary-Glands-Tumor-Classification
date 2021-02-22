# Mammary Glands Tumor Classification

>  Machine learning techniques to distinguish between benignant and malignant tumours in mammary glands.

The aim of this project is to develop an application, based on machine learning algorithms, that allows recognizing if a tumour located on the mammary glands is benignant or malignant.

The number of techniques used throughout the project is extensive and very diverse, ranging from Bayesian classifiers to more complex algorithms, like neuronal networks.

<p align="center">
  <img src='README Images/tumours.png'/ width = 500>
</p>

## Used techniques

To solve the classification problem, several algorithms have been used:

* PCA
* Clustering (with different linkages)
* GLM'S
* Naive Bayes
* K-NN
* K-NN LOOCV
* LDA
* QDA
* Neuronal Network
* Random Forest

<p align="center">
  <img src='README Images/variables.PNG'/>
</p>

## Installation

In order to correctly use the programs provided, it is necessary to have installed the following libraries:

* `library(naivebayes)`
* `library(MASS)`
* `library(klaR)`
* `library(nnet)`
* `library(caret)`
* `library(randomForest)`
* `library(ggplot2)`

To install the requested libraries, the following command should be executed in the [R Studio®](https://rstudio.com/) console:

`install.packages("name_of_package")`

## Architecture

The files contained in this repository are:

* [`R Code`](./Code.Rmd) with all the machine learning techniques.
* An extensive [`report`](./Report.pdf) about the development and conclusions of this project. (Language: Catalan)

*Note: The rest of the files in the master branch are auxiliary or license related*

## Team

This project was developed by:
| [![Vinomo4](https://avatars2.githubusercontent.com/u/49389601?s=60&v=4)](https://github.com/Vinomo4) | 
| --- | 
| [Víctor Novelle Moriano](https://github.com/Vinomo4) | 


Student of Data Science and Engineering at [UPC](https://www.upc.edu/ca).

## License

[MIT License](./LICENSE)
