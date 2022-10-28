---
layout: default
title: 1 Load and View DataFrame
nav_order: 1
parent: Workshop Activities
---
# Load and View DataFrame

## 1. upload a csv. You can use your own of the one provided.
<details>
<summary>Click for navigation help GIF</summary>
<img src="\images\upload-csv.gif">
</details>

## 2. Import the pandas library (I name it "pd" because that's common on help forums)
## 3. Run your first cell

<details>
<summary>Click for code help GIF</summary>
<img src="images\import-pandas.gif">
</details>

## 4. Load your data as a Pandas DataFrame using `pd.read_csv()`
<details>
<summary>Click for code help</summary>
<p>"header = 0" tells the function that your data has headings on row 0</p>
<img src="images\loading-csv.PNG">
</details>

## 5. View the top items in your DataFrame using `df.head()`
<details>
<summary>Click for code help</summary>
<p>by default, <b>head()</b> shows the top 5 rows of your DataFrame, but pass it any number to show more</p>
<img src="images\movie-head.PNG">
</details>

## 6. Start to understand your data by viewing some of it's attributes and methods
`df.shape` [see in docs](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.shape.html#pandas.DataFrame.shape)
`df.columns` [see in docs](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.columns.html#pandas.DataFrame.columns)
`df.size` [see in docs](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.size.html#pandas.DataFrame.size)
`df.dtypes` [see in docs](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.dtypes.html#pandas.DataFrame.dtypes)
`df.count()` [see in docs](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.count.html)

<details>
<summary>Click for code help</summary>
<img src="images\df-shape.PNG">
<img src="images\df-cols.PNG">
<img src="images\df-size.PNG">
<img src="images\df-dtypes.PNG">
<img src="images\df-count.PNG">
</details>

## 7. Go to the [Pandas Documentation](https://pandas.pydata.org/docs/reference/frame.html) and find another attribute or method that helps describe your data

**UPDATE**
[NEXT STEP: Excel Basics](basics-data-cleaning.html){: .btn .btn-blue }
