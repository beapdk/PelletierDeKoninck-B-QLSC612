# QLSC612 assignement for Brainhack school 2020

## PelletierDeKoninck-B-QLSC612

This assignment holds the purpose of demonstrating how researchers can (easily) produce false positives or inflated prediction rates via p-hacking. See complete description with ```practical-assignment.md``` file. 

### Installation requirements

* Python  *(this was based on 3.7.6 version and used via *miniconda*). For Python installation tutorials, refer to either [conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html) or [pip](https://docs.python.org/3/using/index.html)

* Jupyter NoteBook *[Installation documentation](https://jupyter.org/install)

To install the packages required via conda follow these instructions based on this [Documentation](https://docs.anaconda.com/anaconda/user-guide/tasks/install-packages/). 
For installing packages rather via pip you can refer to [this](https://packaging.python.org/tutorials/installing-packages/) instead.

For pandas : ```conda install pandas``` 

*(For a specific version install for any package via conda add ```=(version)```)*, for example : ```conda install pandas=1.0.3 ``` 

For scipy :  ```conda install scipy```

#### Packages needed to install```myanalysis.ipynb```

Please refer to ```requirement.txt``` file for package installation needed or follow the list below: 

* pandas
* numpy
* random2
* matplotlib.pyplot
* statsmodels.formula.api
* statsmodels.api


### Analysis script and data

You can follow the ```myanalysis.ipynb```run by jupyter notebook for full analysis rundown. This file can be found in the PelletierDeKoninck-B-QLSC612/script/ folder of this repos. 
For the data file needed, the file ```brainsize.csv``` can be found in the folder PelletierDeKoninck-B-QLSC612/data/
of this repo. 

### Outputs expected

* Descriptive statistic table of all variables (with the addition of two random seed variables 'partY' and 'partY2')
* Multiple regression model (model_partY) results summary output for predicting partY by factors FSIQ, VIQ and PIQ
* Plots of regression for each factors related to partY
* Plots of residuals for the three independant variables FSIQ, VIQ and PIQ (factors)
* Multiple regression model (model_partY2) result summary output for predicting partY2 by factors FSIQ, VIQ and PIQ




