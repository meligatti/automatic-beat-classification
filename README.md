# Beat classification system

This program was made as the final project from the subject Neural Networks on February 2019.  It downloads a specified ECG record from MIT Long Term Database and the split beats are classified into four groups (normal, ventricular premature, supraventricular premature, and premature AV junctional).

The classification method was implemented with a recurrent neural network. The results are displayed using a confusion matrix.

# Dependences
This project was created on Python 3. As it was showed in a Jupyter Notebook to combine code and text explaining some decisions made, it's mandatory to have Jupyter Lab (or Jupyter Notebook) installed to be able to read and execute it. Later, it uses some packages:

* __wfdb__ to download the ECG records
* __numpy__ for array handling and to perform some calculations
* __matplotlib__ for beat plotting
* __pywt__ for ECG filtering
* __tensorflow__ to create and train the classification model 
* __keras__ as a layer to configure easier all needed on Tensorflow
* __pycm__ to calculate the confusion matrix

