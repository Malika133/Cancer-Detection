# Cancer Detection
## Model Evaluation and Validation
## Project: Cancer Detection
### Install

This project requires Python and the following Python libraries installed:

1. NumPy
2. Pandas
3. matplotlib
4. Pytorch
5. plotly.express
You will also need to have software installed to run and execute a Jupyter Notebook.

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.

### Code

Created an algorithm to identify metastatic cancer in small image patches taken from larger digital pathology scans. The data for this competition is a slightly modified version of the PatchCamelyon (PCam) benchmark dataset.

### Run
In a terminal or command window, navigate to the top-level project directory boston_housing/ (that contains this README) and run one of the following commands:

```
ipython notebook Cancer-Detection.ipynb
```
or open with Jupyter Lab
```
jupyter lab
```

This will open the Jupyter Notebook software and project file in your browser.


### Data

In this dataset, you are provided with a large number of small pathology images to classify. Files are named with an image id. The train_labels.csv file provides the ground truth for the images in the train folder. You are predicting the labels for the images in the test folder. A positive label indicates that the center 32x32px region of a patch contains at least one pixel of tumor tissue. 

#### Features

1. Column 1 consists of Images
2. Column 2 consists of Labels 0 and 1.
