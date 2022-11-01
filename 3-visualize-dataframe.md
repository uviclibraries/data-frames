---
layout: default
title: 3 Visualize DataFrame
nav_order: 2
parent: Workshop Activities
---
# Visualize DataFrame

### 1. Sort your data using `df.sort_values()`. 
Choose which column you would like to sort by using the `by` argument `by= ['column name']`. The column should be numeric for the following steps.
would you like to see the top values or bottom values? Set the `ascending` argument to either `False` or `True`.
<details>
<summary>Click for code help</summary>
<img src="images\data-frames-Activity-03\sort.PNG"/>
</details>

### 2. To avoid overcrowding your visualization, filter for only the top or bottom of your data (whatever you chose in step 1).
For the top use `df.nlargest()`
For the bottom use `df.nsmallest()` 
The first argument is `n`. How many entries would you like to show in your visualization?
The second argument is `columns`. The column or list of columns to order by. In this case, choose 1 column to order by.
<details>
<summary>Click for code help</summary>
<img src="images\data-frames-Activity-03\nlargest.PNG"/>
</details>

### 3. Plot your data using `df.plot()`.
Use the `kind` argument to choose a plot type. [This article](https://towardsdatascience.com/data-visualization-101-how-to-choose-a-chart-type-9b8830e558d6) explains when to choose each kind or plot.
Set the `x` and `y` values by passing the name of a column to each argument.
<details>
<summary>Click for code help</summary>
<p>This example uses a bar chart because it is good for illustrating a small number of categorical variables</p>
<img src="images\data-frames-Activity-03\plot1.PNG"/>
</details>

### 4. Improve your visualization.
Are there any missing labels that could help a viewer understand the chart better?
Are there unnecessary chart elements that clutter the visualization?
What about a title so the view knows what the data represents?
Where you think is appropriate, use the following arguments: `xlabel`, `ylabel`, `title`, `legend`, `grid`, `figsize` [see in docs](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.plot.html)

<details>
<summary>Click for code help</summary>
<p>In this chart, the y-label is in scientific notation, which might not be easy for everyone to read. By adding a descriptive ylabel, it becomes easier to understand that the ticks are in billions.</p>
<p>After adding the y-label, the legend becomes redundant, so it can be removed.</p>
<p> A title is added to explain what the visualization represents.</p>
<img src="images\data-frames-Activity-03\plot2.PNG"/>
</details>

### 5. Save the plot to a file using `your_plot_name.figure.savefig()`.
The argument `bbox_inches="tight"` fits the image size to your plot.
Your image will save in JupyterHub
<details>
<summary>Click for code help</summary>
<img src="images\data-frames-Activity-03\savefig.PNG"/>
</details>

### 6. Download the visualization image file so you can share it.

a. Go to the files page

b. Checkoff the box next to your image file

c. Select Download

<details>
<summary>Click for navigation help</summary>
<img src="images\data-frames-Activity-03\download-plot-img.gif"/>
</details>

You're done! You've now completed the Pandas DataFrames in Jupyter Notebook Workshop. Thanks for joining us.

[NEXT STEP: Earn a Workshop Badge](informal-credentials.md){: .btn .btn-blue }