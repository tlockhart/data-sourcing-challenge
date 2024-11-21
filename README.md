# CME-GST Prediction Dataset Preparation

## Summary

This repository contains a Jupyter Notebook that demonstrates the process of preparing a dataset for predicting Geomagnetic Storms (GSTs) caused by Coronal Mass Ejections (CMEs). These powerful bursts of plasma from the Sun can interact with Earth's magnetic field, potentially disrupting electronic devices such as satellites, GPS systems, and power grids. 

To aid NOAA's Space Weather Prediction Center in improving their prediction capabilities, this project extracts data from the NASA API, specifically from GST and CME data sources. The data is merged and analyzed to compute the average time it takes for a CME to cause a GST. The prepared dataset can later be utilized in Machine Learning models to improve the accuracy of space weather predictions.

For more information about Geomagnetic Storms and their impacts, visit the [NOAA Space Weather Prediction Center](https://www.swpc.noaa.gov/).

---

## Setup

The Jupyter Notebook for this project is named `retrieve_data.ipynb`. Ensure you have the required dependencies installed before proceeding.

### Requirements

1. Python v3.10 or later
2. Jupyter Notebook
3. Visual Studio Code or any other preferred IDE
4. dotenv:
    - pip install python-dotenv

---

## Installation Steps

1. Clone this repository to your local machine:
   ```bash
   git clone git@github.com:tlockhart/cme-gst-dataset.git
2. Request an api key from [Nasa](https://api.nasa.gov/)
3. Create a `.env file` in the project's root directory
    - Add the following line to your .env file
    - NASA_API_KEY="ADD YOUR API_KEY HERE" 
4. Open Visual Studio Code
5. Open the `retrieve_data.ipynb` jupyter notebook.
6. Select Run All
7. Select Python 3.10.4.1, if prompted for kernel
