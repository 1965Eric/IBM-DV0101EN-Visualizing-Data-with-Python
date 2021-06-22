## Module Introduction

In this module, you learn about area plots and how to create them with Matplotlib, histograms and how to create them with Matplotlib, bar charts, and how to create them with Matplotlib, pie charts, and how to create them with Matplotlib, box plots and how to create them with Matplotlib, and scatter plots and bubble plots and how to create them with Matplotlib.

## Learning Objectives

In this lesson you will learn about:

* Explain how to generate an area plot using Matplotlib
* Describe why and how to create histograms using Matplotlib
* Explain how to create bar charts
* Create pie charts using Matplotlib
* Create a box plot using Matplotlib

## Basic Visualization Tools

[Basic Visualization Tools](https://github.com/1965Eric/IBM-DV0101EN-Visualizing-Data-with-Python/blob/main/DV0101EN-Exercise-Area-Plots-Histograms-and-Bar-Charts-py.ipynb)

## Graded Quiz

Question 1: Area plots are stacked by default.

- A. [X] True
- B. [ ] False

Question 2: Given a *pandas* series, **series_data**, which of the following will create a histogram of series_data and align the bin edges with the horizontal tick marks?

- A. [ ]

```
count, bin_edges = np.histogram(series_data)
series_data.plot(kind='hist', xticks = count, bin_edges)
```

- B. [ ]

```
count, bin_edges = np.histogram(series_data)
series_data.plot(kind='hist', xticks = count)
```

- C. [X]

```
count, bin_edges = np.histogram(series_data)
series_data.plot(kind='hist', xticks = bin_edges)
```

- D. [ ] 

```
series_data.plot(kind='hist')
```

Question 3: Given a *pandas* dataframe, **question**, which of the following will create a horizontal barchart of the data in **question**?

- A. [ ] ```question.plot(type='bar', rot=90)```
- B. [ ] ```question.plot(kind='bar', orientation='horizontal')```
- C. [X] ```question.plot(kind='barh')```
- D. [ ] ```question.plot(kind='bar')```

