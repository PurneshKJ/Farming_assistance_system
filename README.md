# Farming Assistance System

Farming Assistance System helps to identify diseases in the plants, detect weeds near the plants and recommend suitable crops using Machine learning algorithms and IoT devices.

It consist of three components:

- Plant leaf health predictor: Identify diseases based on the images of the leaves.
- Weed dectection system: Detect the weeds growing near the plants in the given images.
- crop recommendation system: Recommend suitable crops for cultivation based on data like soil nutrient content, temperature, humidity, soil moisture, pH value and rainfall.

# Dataset

For training the models for each component following dataset where used.

- Plant leaf health predictor: Plant village repository which can be downloaded from https://data.mendeley.com/datasets/tywbtsjrjv/1
- Weed dectection system: Images of the weeds and crops with the bounding boxes can be dowloaded from https://www.kaggle.com/ravirajsinh45/crop-and-weed-detection-data-with-bounding-boxes
- crop recommendation system: CSV file containing the data for recommendation can be downloaded from https://www.kaggle.com/atharvaingle/crop-recommendation-dataset

All the downloaded data must be uzipped and copied to a folder named "data" in the project folder.

# Installation

1. Install Anaconda [ https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html ]
2. Create a conda environment with the requirements.txt file
3. Install Jupyter notebook 

```bash
conda install -c conda-forge notebook 
```
# Usage

Run the jupyter notebook in the src folder.