---
layout: default
title: 1 Load and View DataFrame
nav_order: 2
parent: Workshop Activities
---
# Load and View DataFrame

### 1. upload a csv. You can use your own or the one provided.
<details>
<summary>Click for navigation help GIF</summary>
<img src="images\data-frames-Activity-01\upload-csv.gif">
</details>

### 2. Import the pandas library (I name it "pd" because that's common on help forums)

<details>
<summary>Click for code help GIF</summary>
<img src="images\data-frames-Activity-01\import-pandas.gif">
</details>

### 3. Run your first cell

<details>
<summary>Click for navigation help GIF</summary>
<img src="images\data-frames-Activity-01\import-pandas.gif">
</details>

### 4. Load your data as a Pandas DataFrame using `pd.read_csv()`
<details>
<summary>Click for code help</summary>
<p>"header = 0" tells the function that your data has headings on row 0</p>
<img src="images\data-frames-Activity-01\loading-csv.PNG">
</details>

### 5. View the top items in your DataFrame using `df.head()`
<details>
<summary>Click for code help</summary>
<p>by default, <b>head()</b> shows the top 5 rows of your DataFrame, but pass it any number to show more</p>
<img src="images\data-frames-Activity-01\movie-head.PNG">
</details>

### 6. Start to understand your data by viewing some of it's attributes and methods
Make a new cell and Input `df.shape`. Run the cell. [see in docs](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.shape.html#pandas.DataFrame.shape)

Make a new cell and Input `df.columns`. Run the cell. [see in docs](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.columns.html#pandas.DataFrame.columns)

Make a new cell and Input `df.size`. Run the cell. [see in docs](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.size.html#pandas.DataFrame.size)

Make a new cell and Input `df.dtypes`. Run the cell. [see in docs](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.dtypes.html#pandas.DataFrame.dtypes)

Make a new cell and Input `df.count()`. Run the cell. [see in docs](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.count.html)

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

[NEXT STEP: Excel Basics](2-edit-dataframe){: .btn .btn-blue }
