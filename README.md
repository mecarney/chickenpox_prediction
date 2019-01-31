# Chickenpox Prediction

This is an experiment in working with RNNs using Python and Keras to predict reported numbers of chickenpox cases in NYC. The final model predicts case numbers by month with an accuracy over 99%.

## Getting Started

From the command line:<br />
`python3 -m venv chickenpox_prediction`<br />
`source chickenpox_prediction/bin/activate`<br />
`python3 -m pip install --upgrade https://storage.googleapis.com/tensorflow/mac/cpu/tensorflow-1.12.0-py3-none-any.whl`<br />
`pip install -r requirements.txt`<br />
`jupyter notebook chickenpox_prediction.ipynb`

## Data and Predictions
<img src="https://github.com/mecarney/chickenpox_prediction/blob/master/dataset.png" height="433" title="Dataset"> <img src="https://github.com/mecarney/chickenpox_prediction/blob/master/prediction.png" height="433" title="Predictions">

## Acknowledgments
Dataset downloaded from [datamarket.com](https://datamarket.com/data/set/22v7/monthly-reported-number-of-chickenpox-new-york-city-1931-1972#!ds=22v7&display=line)
