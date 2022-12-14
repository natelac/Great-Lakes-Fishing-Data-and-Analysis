# Great Lakes Fishing Data and Analysis

This repository contains a real world fishing dataset and the notebooks used to clean and analyse it.

[![](https://github.com/natelac/Great-Lakes-Fishing-Data-and-Analysis/blob/main/Fish.png)]()

## The notebooks

The goal of these notebooks is to clean the data into a presentable form, perform simple data analysis and exploration, and fit some models for predicting good fishing days. If some of the graphs are too small, you want to checkout the EBM model, or you want to run the code- use the google colab version.

---

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/drive/folders/1G9bTWalcd1IADgLsdGyDG5u_tdz0LGqU?usp=share_link)

[`00-Introduction-and-Index.ipynb`](notebooks/00-Introduction-and-Index.ipynb)

[`01-Cleaning.ipynb`](notebooks/01-Cleaning.ipynb)

[`02-Introduction-and-Index.ipynb`](notebooks/02-Fetching-Historical-Weather.ipynb)

[`03-Data-Analysis.ipynb`](notebooks/03-Data-Analysis.ipynb)

[`04-Model-Fitting.ipynb`](notebooks/04-Model-Fitting.ipynb)

[`05-Summary.ipynb`](notebooks/05-Summary.ipynb)

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
