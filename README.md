# Google Play Store Exploratory Analysis

## Project
In this project we'll be exploring a dataset containing 10 thousand Google Play Store apps ([dataset available on kaggle](https://www.kaggle.com/lava18/google-play-store-apps)).

We'll be using data visualizations to answer some questions:

1. What are the most common app categories on Google Play Store?
2. What are the most popular app categories? (number of downloads/installs)
3. How is the rating distribution? (Overall, Categories, Free Apps x Paid Apps)
4. How is the pricing distribution? (Paid x Free, Average Price)
5. What is the average size of an app?
6. How is the content rating distribution for apps?
7. What is the minimum android version required by most apps?
8. What are the most common words in reviews?

To view the visualizations, [click here](https://github.com/kimurarh/googleplay-analysis/tree/main/visualization#Visualization)

## Technologies
The following technologies were used in this analysis:

* Python
  * Jupyter
  * Numpy
  * Pandas
  * Matplotlib
  * Seaborn
  * Squarify
  * Wordcloud

## File Organization

    .
    ├── datasets                                # Google Play Store datasets from Kaggle 
    │   ├── googleplaystore.csv                 
    │   └── googleplaystore_user_reviews.csv              
    ├── imgs
    |   ├── ipynb-file-image.png                # Documentation image
    |   └── mask-image.png                      # Mask image to generate WordCloud           
    ├── Visualization
    |   ├── *.png                               # Visualizations                
    |   └── README.md                           # Visualizations documentation
    ├── Google-Play-Store-Analysis.ipynb        # Jupyter notebook
    ├── environment.yml                         # Conda environment
    └── README.md                               # Documentation

## Development
Create the conda environment from the environment.yml file available in this repository:
```
conda env create -f environment.yml
```
Activate the conda environment:
```
conda activate netflix-analysis
```
Launch jupyter notebook:
```
jupyter notebook
```
Click on the Google-Play-Store-Analysis.ipynb file:

![ipynb file image](imgs/ipynb-file-image.png)
