# Copernicus - Framework
### *In Development*
Copernicus is the stand-alone high-level Deep Learning framework which serves as the **data pre-processing** and **dynamic-NN** engine for **Copernicus Alpha**. This entire framework is built using jupyter notebooks and each module exist within the ```exp``` directory. 

## About
Building Deep Learning models is known as much of an 'art' as a science. Copernicus attempts to merge the two - where the art becomes more of the dataset and the science is fully automated by AI itself. The philosophy behind this project is to make optimized model building as simple as possible - allowing for anyone with data to build a *regression* or *classification* algorithm on the fly. 

## Installing
To begin simply clone this repository and perform the following: 
1. install PyTorch: https://pytorch.org/
2. install requirements (common data science tools used - if you have anaconda installed ignore this): ```pip install requirements.txt```

## Notebooks
As this entire framework is built via **jupyter notebooks** all testing, and modules are built in seperate notebooks. 

* ```copernicus_datasets```: A notebook to download all experimental datasets used to create and test the framework
* ```copernicusActivations_*```: Notebooks containing activation functions used
    * ```exp/nb_copernicusActivations``` contains all logic
* ```copernicusTabular_*```: Notebook breaking down everything in the pre-processing engine.
* ```copernicusLearner_*```: Notebook breaking down everything in dynamic-NN engine.

### ```copernicusTabular```
The main data pre-processing component is our *tabular module*. This will take a raw dataset and:
1. Remove excessive null values
2. Fill non-excessive null values with appropriate placements
3. Normalize all continuous data
4. Structure and format for our ```Learner```

## NOTE
This project is actively in development and updates will be made daily. 