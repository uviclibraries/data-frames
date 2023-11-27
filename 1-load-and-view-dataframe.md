---
layout: default
title: 1 Load and View DataFrame
nav_order: 2
parent: Workshop Activities
---
# Load and View DataFrame

### 1.a. You can use your own data or [the one provided](https://raw.githubusercontent.com/uviclibraries/data-frames/main/student-files/Highest%20Hollywood%20Grossing%20Movies.csv){:target="_blank"}. 

**Go to** the linked URL, right click, select **save as**. 


### 1.b. Upload Your CSV and start a new notebook

1. Go to [syzygy](https://uvic.syzygy.ca/) and log in using your Netlink ID
2. Your launch screen should have 2 sections. Your files/ directories on the right and the "launcher" on the left.
<img src="images\data-frames-Activity-01\launch-screen.png">
3. Select the **upload** button on the files side (right) and select your data file from step 1.a.
<img src="images\data-frames-Activity-01\upload-button.png">
4. open a new Python Notebook by clicking on **Python 3 (ipykernel)** under the **Notebook** section on the Launcher side (left)
<img src="images\data-frames-Activity-01\launch-python-notebook.png">

<mark> Make sure your data file and notebook are in the same folder/ directory! </mark>

### 2. Import the pandas library by typing `import pandas as pd` in the first cell (I name it "pd" because that's common on help forums)

<img src="images\data-frames-Activity-01\import-pandas.gif">

### 3. Run the cell that you just wrote in:

1. Make sure it is selected (it should be outlined with a blue or green bar next to it)
2. Click on **Run** in the top navigation pane

<img src="images\data-frames-Activity-01\run-button.PNG">

<details>
<summary>Show/Hide Animation</summary>
<img src="images\data-frames-Activity-01\import-pandas.gif">
</details>

### 4. Load your data as a Pandas DataFrame using `pd.read_csv()`. 

1. Inside the brackets, [the first argument](https://www.w3schools.com/python/gloss_python_function_arguments.asp#:~:text=The%20terms%20parameter%20and%20argument,function%20when%20it%20is%20called.), write your csv file name in quotes (as a string).
2. The second argument you can include is `header=0` which tells the method that your data has headers on row 0.

I call the DataFrame `df` because that is convention in documentation and help forums, but you can call it whatever you'd like.

<details>
<summary>Click for code help</summary>
<p>"header = 0" tells the function that your data has headings on column 0</p>
<img src="images\data-frames-Activity-01\loading-csv.PNG">
</details>

### 5. View the top items in your DataFrame using `df.head()`. by default, `head()` shows the top 5 rows of your DataFrame, but pass it any number (less than the number of rows you have) to show more.

<details>
<summary>Click for code help</summary>
<img src="images\data-frames-Activity-01\movie-head.PNG">
</details>

### 6. Start to understand your data by viewing some of it's attributes and methods
Make a new cell and Input `df.shape`. Run the cell. This returns a [tuple](https://www.w3schools.com/python/python_tuples.asp) with the first value being the number of rows, and the second value being the number of columns [see in docs](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.shape.html#pandas.DataFrame.shape)

Make a new cell and Input `df.columns`. Run the cell. This returns the name of the columns, or the headers [see in docs](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.columns.html#pandas.DataFrame.columns)

Make a new cell and Input `df.size`. Run the cell. This returns the number of items in your data frame (number of rows x number of columns) [see in docs](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.size.html#pandas.DataFrame.size)

Make a new cell and Input `df.dtypes`. Run the cell. dtypes are the python data type of the values in a cell and also help describe the size of the data. Columns with mixed types are stored with the `object` dtype. [see in docs](https://pandas.pydata.org/docs/user_guide/basics.html#dtypes)

Make a new cell and Input `df.count()`. Run the cell. count the number of items in each col. If the total number is less than the number of rows, then there are blanks. [see in docs](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.count.html)

<details>
<summary>Click for code help</summary>
<img src="images\data-frames-Activity-01\df-shape.PNG">
<img src="images\data-frames-Activity-01\df-cols.PNG">
<img src="images\data-frames-Activity-01\df-size.PNG">
<img src="images\data-frames-Activity-01\df-dtypes.PNG">
<img src="images\data-frames-Activity-01\df-count.PNG">
</details>

### 7. View descriptive statistics with `df.describe()`. This will automatically calculated descriptive statistics using the numeric type rows in your DataFrame
<details>
<summary>Click for code help</summary>
<img src="images\data-frames-Activity-01\df-describe.PNG">
</details>

### 8. Go to the [Pandas Documentation](https://pandas.pydata.org/docs/reference/frame.html) and find another attribute or method that helps describe your data
Input and Run it in a new cell.

[NEXT STEP: Edit DataFrame](2-edit-dataframe){: .btn .btn-blue }
