# Project Name
> Melanoma Cancer Detection 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- ISIC Data Reading & CNN Model creation
- Background of your project: Develop a CNN Model to detect Melanoma Cancer using ISIC Dataset.
- Business probem that this project is trying to solve: understand data organization & create CNN model with best set of hyper parameters to detect Melanoma cancel on given dataset. 
- Datset Used: ISIC Dataset is provided with 9 different types of cancer.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
 1. Model created using given dataset has good accuracy but it is heaviy overfit as model did not perform well on training dataset. 
 2. BatchNormalization & Dropout layer did not improve the model significantly 
 2. Given dataset has imbalance & augmented the data with 500 images of each type to create more balanced dataset.
 3. Final model is looks better with improved accuracy & reduced loss.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Below Python modules used in this case study
- numpy
- pandas
- matplotlib
- Keras
- TensorFlow

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@JPHere007] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
