# Forecasting Carbon Intensity and Solar Generation in the Building Sector

This repository contains code for my Bachelor's thesis on forecasting carbon intensity and solar generation. The data for this project was taken from the [NeurIPS 2023 CityLearn Challenge](https://www.aicrowd.com/challenges/neurips-2023-citylearn-challenge).

The project consists of three main directories:

1. **Data** - Contains all required datasets. The original competition files are in the *original* sub-directory. The *results* and *train-test-split* sub-directories contain the output files from the models and preprocessing steps, respectively. 

2. **Data_preprocessing** - Contains Jupyter notebooks (`.ipynb`) detailing data visualization and preprocessing. 

3. **Models** - Contains the three main notebooks, one for each evaluated model (MLP, LSTM, and GRU). Additionally, a final notebook that combines and compares the results is included. *Note: Running these notebooks will overwrite the previously acquired results stored in the Data directory.*

### Running the Code
Ensure all requirements are installed before running. All files can be executed independently of each other, as all preprocessing steps have already been completed and the output results are saved.
