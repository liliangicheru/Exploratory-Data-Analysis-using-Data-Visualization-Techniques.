# Exploratory-Data-Analysis-using-Data-Visualization-Techniques.

Exploratory Data Analysis using Data Visualization Techniques.
Exploratory Data Analysis (EDA) is a key step in the data analysis process. Data visualization techniques bring Data to life, by making it accessible and understandable-and especially to people not adept to the tech world and help to understand the characteristics of your dataset. Data visualizations, either through shapes, graphs, patterns or colors, provide a better way in which we can perceive information.
**Visualization techniques using python.** 

**Histograms-**  Visualize the distribution of a numerical variable, illustrate the distribution of data, making it easy to spot trends and outliers.

**See below example.**

```python
import matplotlib.pyplot as plt

import numpy as np

data = np.random.randn(1000)### use your dataset

plt.hist(data, bins=20, color='green', edgecolor='black')

plt.title('Histogram Example')

plt.xlabel('Value')

plt.ylabel('Frequency')

plt.show()
```

**Box Plots-**  This technique Show the summary statistics of a numerical variable, including the median, quartiles, and outlier, allowing you to grasp data variability from a glance.

**Below is an example. **

import matplotlib.pyplot as plt

import numpy as np

np.random.seed(2)

dataSet = np.random.normal(100, 25, 200)

print(dataSet)

figure = plt.figure(figsize =(10, 8))

plt.boxplot(dataSet)

plt.show()






** Bar charts- ** Bar charts are an excellent way for comparing categorical data. enabling you to easily identify which categories are most prevalent and identify trends or animalities.
**Below is an example.**

import matplotlib.pyplot as plt

categories = [' A', 'B', ' C',' D']

values = [10, 20, 15 ,5]

plt.bar(categories, values, color='skyblue')

plt.title('Bar Chart Example')

plt.xlabel('Category')

plt.ylabel('Value')

plt.show()



**Scatter Plots:**
Visualize the relationship between two numerical variables.
**Below is an example.**

import matplotlib.pyplot as plt

import numpy as np

x=5

y=30

plt.scatter(x, y, color="purple", marker="o")

plt.title(" Scatter Plot") ###Insert your title

plt.xlabel("X variable") ###the x variable

plt.ylabel("Y variable") ##y-axis label

plt.show()

**Line and making each point with a circle.**

**See example below.**

import matplotlib.pyplot as plt

import numpy as np


ypoints = np.array([3, 8, 1, 10])


plt.plot(ypoints, marker = 'o')

plt.show()


**Summary**

Exploratory data analysis is an iterative process, and the choice of visualization techniques depends on your data and objectives. You can combine multiple techniques to gain a deeper understanding of your data and uncover important patterns and insights.

