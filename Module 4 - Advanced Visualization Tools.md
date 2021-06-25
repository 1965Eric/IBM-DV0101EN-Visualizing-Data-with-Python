## Module Introduction

In this module, you will learn about advanced visualization tools such as waffle charts and word clouds and how to create them. You will also learn about seaborn, which is another visualization library, and how to use it to generate attractive regression plots. In addition, you will learn about Folium, which is another visualization library, designed especially for visualizing geospatial data. Finally, you will learn how to use Folium to create maps of different regions of the world and how to superimpose markers on top of a map, and how to create choropleth maps.

## Learning Objectives

In this lesson you will learn about:

* Apply advanced visualization tools to create waffle charts and word clouds.
* Use Seaborn with Matplotlib to generate attractive regression plots.
* Explain how to use the Folium, for visualizing geospatial data.
* Use Folium to create maps and superpose markers.
* Create Choropleth Maps with Folium.

## Waffle Charts, Word Clouds, and Regression Plots

[Waffle Charts, Word Clouds, and Regression Plots](https://github.com/1965Eric/IBM-DV0101EN-Visualizing-Data-with-Python/blob/main/DV0101EN-Exercise-Waffle-Charts-Word-Clouds-and-Regression-Plots-py.ipynb)

[PyWaffle](https://github.com/1965Eric/IBM-DV0101EN-Visualizing-Data-with-Python/blob/main/PyWaffle.ipynb) is an open source, MIT-licensed Python package for plotting waffle charts.

## Graded Quiz

Question 1: Which of the choices below will create the following regression line plot, given a *pandas* dataframe, **data_dataframe**?

- A. [ ]

```
import seaborn as sns
ax = sns.regplot(x="year", y="total", data=data_dataframe, color="green")
```

- B. [ ]

```
data_dataframe.plot(kind="regression", color="green", marker="+")
```

- C. [X]

```
import seaborn as sns
ax = sns.regplot(x="year", y="total", data=data_dataframe, color="green", marker="+")
```

- D. [ ]

```
data_dataframe.plot(kind="regplot", color="green", marker="+")
```

- E. [ ]

```
import seaborn as sns
ax = sns.regplot(x="total", y="year", data=data_dataframe, color="green")
```

Question 2: In Python, creating a waffle chart is straightforward since we can easily create one using the scripting layer of Matplotlib.

- A. [ ] True
- B. [X] False

