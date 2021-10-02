# Data Folder Details
All data related to the project will be stored in this folder **locally** in your machine. This folder is intended to organize the data processing from the original data to the processed data ready for modelling.

## How to use this section properly?
In order to maintain a healthy workflow when dealing with data, this folder is divided into three sections, each one with a specific purpose for data:

1. **`raw/`** folder is used only to store the original data from [Kaggle's competition](https://www.kaggle.com/c/competitive-data-science-predict-future-sales/), without any changes. To download the data used for this competition please refer to this [url](https://www.kaggle.com/c/competitive-data-science-predict-future-sales/data).
2. **`interim/`** folder is used to save processed data that is not ready for modelling but will be useful to prepare the final data for the modelling process.
3. **`processed/`** is used to save only the final data that will be used for modelling.

> ### ⚠️ IMPORTANT NOTE: ⚠️ 
> As a best practice don't save any kind of data inside github. This because github is not a tool to version data. Instead try to download data from original source or download it through a script.