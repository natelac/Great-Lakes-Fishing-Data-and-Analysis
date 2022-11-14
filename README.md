# Great Lakes Fishing Data and Analysis

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/drive/folders/1G9bTWalcd1IADgLsdGyDG5u_tdz0LGqU?usp=share_link)

This repository contains a real world fishing dataset and the notebooks used to clean and analyse it.

[![](https://github.com/natelac/Great-Lakes-Fishing-Data-and-Analysis/blob/main/Fish.png)]()


## The dataset

The fishing dataset used in these notebooks was collected from over 10 years of fishing on the south shore of Lake Superior- the largest fresh water lake on the planet. The dataset has an entry for every fish caught, almost 2,000 over the last 10 years, and includes simple weather metrics around when the fish was caught along with some information on the fish caught. The logs contain some useful information and context for each fish, however they (and other columns) contain sensitive information. For that reason the raw data is not shared and the cleaned data is available instead. You can get a clean version of the data in the `data` directory.

## The notebooks

The goal of these notebooks is to clean the data into a presentable form, use online weather APIs to collect more information, perform simple data analysis and exploration, and fit some models for predicting good fishing days. Checkout the `notebooks` directory starting with the [Introduction and Index](https://github.com/natelac/Great-Lakes-Fishing-Data-and-Analysis/blob/main/notebooks/00-Introduction-and-Index.ipynb). If some of the graphs are too small or you want to checkout the EBM model, use the [google colab](https://drive.google.com/drive/folders/1G9bTWalcd1IADgLsdGyDG5u_tdz0LGqU?usp=share_link) version.

## Acknowledgements

The fisherman who collected this data is my father, and he was kind enough to let me share the cleaned version with anyone who might want to explore it. He hopes that this data might inspire you to put your models into practice and go out and fish!

## Todo
- Use `pip freeze` to create a list of dependancies for the `.ipynb` files
- Create a `data_description.txt describing` each of the features and how to interpret them
- Finish `02-Fetching-Historical-Weather.ipynb`
- Finish `05-Summary.ipynb`
