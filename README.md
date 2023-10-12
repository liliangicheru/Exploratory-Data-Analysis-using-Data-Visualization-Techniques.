# Exploratory-Data-Analysis-using-Data-Visualization-Techniques.
Exploratory Data Analysis using Data Visualization Techniques.
Exploratory Data Analysis (EDA) is a key step in the data analysis process. Data visualization techniques bring Data to life, by making it accessible and understandable-and especially to people not adept to the tech world and help to understand the characteristics of your dataset. Data visualizations, either through shapes, graphs, patterns or colors, provide a better way in which we can perceive information.
Visualization techniques using python. 
Histograms- Visualize the distribution of a numerical variable, illustrate the distribution of data, making it easy to spot trends and outliers.

**See below example.**

import matplotlib.pyplot as plt

import numpy as np

data = np.random.randn(1000)### use your dataset

plt.hist(data, bins=20, color='green', edgecolor='black')

plt.title('Histogram Example')

plt.xlabel('Value')

plt.ylabel('Frequency')

plt.show()
