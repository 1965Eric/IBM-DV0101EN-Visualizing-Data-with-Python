## Module Introduction

In this module, you will get started with dashboard creation using the Plotly library.  You will create a dashboard with the theme "US Domestic Airline Flights Performance". You will do this using a US airline reporting carrier on-time performance dataset, Plotly, and Dash concepts learned throughout the course. Hands-on labs will follow each concept to make you comfortable with using the library. Reading lists will reference additional resources to learn more about the concepts covered. 

## Learning Objectives

* Identify high-level popular Python dashboarding tools.
* Demonstrate basic Plotly, Plotly.graph_objects, and Plotly express commands.
* Demonstrate using Dash and basic Dash components (core and HTML).
* Demonstrate adding different dashboard elements including text boxes, dropdowns, graphs, and others.
* Apply interactivity to dash core and HTML components.
* Describe how a dashboard can be used to answer critical business questions.

## Additional Resources for Dashboards

For more information about Dashboards, visit the following links:

[Python dashboarding tools](https://pyviz.org/dashboarding/)

[John Snow's data journalism](https://www.theguardian.com/news/datablog/2013/mar/15/john-snow-cholera-map)

## Additional Resources for Plotly

To learn more about using Plotly to create dashboards, explore

[Plotly Python](https://plotly.com/python/getting-started/)

[Plotly graph objects with example](https://plotly.com/python/graph-objects/)

[Plotly express](https://plotly.com/python/plotly-express/)

[API reference](https://plotly.com/python-api-reference/)

Here are additional useful resources:

[Plotly cheatsheet](https://images.plot.ly/plotly-documentation/images/plotly_js_cheat_sheet.pdf)

[Plotly community](https://community.plotly.com/c/api/5)

[Related blogs](https://plotlygraphs.medium.com)

[Open-source datasets](https://developer.ibm.com/exchanges/data/)

## Plotly Basics - Scatter, Line, Bar, Bubble, Histogram, Pie, Sunburst

[Plotly Basics](https://github.com/1965Eric/IBM-DV0101EN-Visualizing-Data-with-Python/blob/main/DV0101EN-Plotly-Basics.ipynb)

## Additional Resources for Dash

To learn more about Dash, explore:

[Complete dash user guide](https://dash.plotly.com)

[Dash core components](https://dash.plotly.com/dash-core-components)

[Dash HTML components](https://dash.plotly.com/dash-html-components)

[Dash community forum](https://community.plotly.com/c/dash/16)

[Related blogs](https://medium.com/plotly/tagged/dash)

## Dash Basics - HTML and Core Components, Multiple Charts

[Dash Basics](https://github.com/1965Eric/IBM-DV0101EN-Visualizing-Data-with-Python/blob/main/dash_basics.py)

## Additional Resources for Interactive Dashboards

To learn more about making interactive dashboards in Dash, visit:

[Python decorators reference 1](https://realpython.com/primer-on-python-decorators/)

[Python decorators reference 2](https://www.python.org/dev/peps/pep-0318/#current-syntax)

[Callbacks with example](https://dash.plotly.com/basic-callbacks)

[Dash app gallery](https://dash-gallery.plotly.host/Portal/)

[Dash community components](https://plotly.com/dash-community-components/)

## Add interactivity: user input and callbacks

[Add interactivity](https://github.com/1965Eric/IBM-DV0101EN-Visualizing-Data-with-Python/blob/main/dash_interactivity.py)

## Flight Delay Time Statistics Dashboard

Flight Delay Time Statistics Dashboard

## Reading: Summary

* Best dashboards answer critical business questions. It will help businesses make informed decisions, thereby improving performance. 
* Dashboards can produce real-time visuals. 
* Plotly is an interactive, open-source plotting library that supports over 40 chart types. 
* The web-based visualizations created using Plotly python can be displayed in Jupyter notebook, saved to standalone HTML files, or served as part of pure Python-built web applications using Dash. 
* Plotly Graph Objects is the low-level interface to figures, traces, and layout whereas Plotly express is a high-level wrapper for Plotly. 
* Dash is an Open-Source User Interface Python library for creating reactive, web-based applications. It is both enterprise-ready and a first-class member of Plotly’s open-source tools. 
* Core and HTML are the two components of Dash. 
* The dash_html_components library has a component for every HTML tag. 
* The dash_core_components describe higher-level components that are interactive and are generated with JavaScript, HTML, and CSS through the React.js library. 
* A callback function is a python function that is automatically called by Dash whenever an input component's property changes. Callback function is decorated with $@app.callback$ decorator. 
* Callback decorator function takes two parameters: Input and Output. Input and Output to the callback function will have component id and component property. Multiple inputs or outputs should be enclosed inside either a list or tuple. 
