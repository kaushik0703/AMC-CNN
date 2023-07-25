# AMC-CNN
Automatic modulation Classification for Low Powered Iot devices using convolutional neural networks by different architechtures like mobilenet 


## Dataset

The Projects Dataset is taken from Deepsig RadioMl which is a synthetic dataset, generated with GNU Radio, consisting of 11 modulations. This is a variable-SNR dataset with moderate LO drift, light fading, and numerous different labeled SNR increments for use in measuring performance across different signal and noise power scenarios.

Download Dataset [here](https://www.deepsig.ai/datasets)

## Run 

RML_Model contains model file 

RML3 file contains python code for running this model,dataset

1. Download and Import Dataset like mentioned here

``` python
with open("./RML2016.10c_dict.pkl", 'rb') as f:       #Dataset = RML 2016.10c
```

2. After importing just run the file Python RML3_7.py

