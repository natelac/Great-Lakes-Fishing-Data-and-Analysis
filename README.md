# Great Lakes Fishing Data and Analysis

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/drive/folders/1G9bTWalcd1IADgLsdGyDG5u_tdz0LGqU?usp=share_link)

This repository contains a real world fishing dataset and the notebooks used to clean and analyse it.

## The notebooks

The goal of these notebooks is to clean the data into a presentable form, perform simple data analysis and exploration, and fit some models for predicting good fishing days. The notebooks are located in the [`notebooks`](notebooks/) directory. If some of the graphs are too small or you want to checkout the EBM model, use the [google colab](https://drive.google.com/drive/folders/1G9bTWalcd1IADgLsdGyDG5u_tdz0LGqU?usp=share_link) version.

## The dataset

The fishing dataset used in the notebooks was collected from over 10 years of fishing on the south shore of Lake Superior- the largest fresh water lake on the planet. The dataset has an entry for every fish caught, almost 2,000 over the last 10 years, and includes simple weather metrics around when the fish was caught along with some information on the fish caught. The logs contain some useful information and context for each fish, however they (and other columns) contain sensitive information. For that reason the raw data is not shared and the cleaned data is available instead. You can get a clean version of the data in the [`data`](data/) directory.

## Some findings

Here is a static dashboard showing the top factors that affected the quality of fishing trips on Lake Superior. Read the notebooks for a full analysis and many more graphs! If the image is rendering a bit small for you, [here](https://github.com/natelac/Great-Lakes-Fishing-Data-and-Analysis/blob/main/Overview_light.png) is a bigger version

[![](https://github.com/natelac/Great-Lakes-Fishing-Data-and-Analysis/blob/main/Overview_light.png)]()

## Acknowledgements

The fisherman who collected this data is my father (not me!), and he was kind enough to let me share the cleaned version with anyone who might want to explore it. He hopes that this data might inspire you to put your models into practice and go out and fish!

## Todo
- Get the rest of the 2013 data
- Create a `data_description.txt` describing each of the features
- Use `pip freeze` to create a list of dependancies for the `.ipynb` files
