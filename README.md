# Data Visualization with R and ggplot2

These materials make use of the data from Kaggle's [Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic) competition.

This project mainly uses R for data visualization. The data visualized here is on titanic's dataset, which analyzes data such as survival rate vs. Age, survival rate vs. Gender, etc.

It uses the package ggplot2 which is a library in R used for making plots for visualization.
It can be installed in your R console using

```
install.packages("ggplot2")
```

It also uses the package `mongolite`, as the csv was originally loaded on a MongoDB cluster, and the data is queried from there in R.
