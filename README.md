# Bike Sharing Data Analysis

This repository contains the exploratory data analysis (EDA) of a bike sharing dataset. In this project, we aim to gain insights and extract meaningful information from the dataset using various data visualization and analysis techniques.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Getting Started](#getting-started)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

Bike sharing systems are becoming increasingly popular in urban areas as a convenient and eco-friendly mode of transportation. This project focuses on analyzing a bike sharing dataset to uncover patterns, trends, and relationships within the data.

## Dataset

The dataset used for this analysis can be found [here](https://www.kaggle.com/datasets/lakshmi25npathi/bike-sharing-dataset?resource=download).

The dataset includes the following columns:

  - `instant`: record index
	- `dteday` : date
	- `season` : season (1:springer, 2:summer, 3:fall, 4:winter)
	- `yr` : year (0: 2011, 1:2012)
	- `mnth` : month ( 1 to 12)
	- `hr` : hour (0 to 23)
	- `holiday` : weather day is holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
	- `weekday` : day of the week
	- `workingday` : if day is neither weekend nor holiday is 1, otherwise is 0.
	- `weathersit` :- 1: Clear, Few clouds, Partly cloudy, Partly cloudy
		              - 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
		              - 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
		              - 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
	- `temp` : Normalized temperature in Celsius. The values are divided to 41 (max)
	- `atemp`: Normalized feeling temperature in Celsius. The values are divided to 50 (max)
	- `hum`: Normalized humidity. The values are divided to 100 (max)
	- `windspeed`: Normalized wind speed. The values are divided to 67 (max)
	- `casual`: count of casual users
	- `registered`: count of registered users
	- `cnt`: count of total rental bikes including both casual and registered

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine using:
2. Navigate to the project directory:
3. Install the required dependencies:


## Exploratory Data Analysis

In this section, we explore the dataset and analyze its various attributes. The analysis includes but is not limited to:
- Data cleaning and preprocessing.
- Visualization of key statistics.
- Identification of trends in bike usage over time.
- Correlation between weather conditions and bike rentals.

## Usage

Describe how to run the analysis code and any scripts provided in the repository. Provide step-by-step instructions so that others can reproduce your findings.

For example:
1. Run the `BIKE DATASET HOURS.ipynb` notebook using Jupyter Notebook or Jupyter Lab.
2. Follow the code and comments to understand the analysis process.
3. Modify parameters or sections as needed for your own analysis.

## Contributing

Contributions are welcome! If you find any issues or want to enhance the analysis, feel free to open an issue or submit a pull request.

1. Fork this repository.
2. Create a new branch: `git checkout -b feature-new-analysis`
3. Make your changes and commit them: `git commit -m 'Add new analysis on XYZ'`
4. Push to the branch: `git push origin feature-new-analysis`
5. Open a pull request.


