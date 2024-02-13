---
layout: default
title: Activities Introduction
nav_order: 1
parent: Workshop Activities
---
# Hands-On Activities Introduction

Please review the following [Introductory Slides](https://www.canva.com/design/DAFQFA5VsAU/IKlz3Xeh5q1EJKWgeRr6ng/view?utm_content=DAFQFA5VsAU&utm_campaign=designshare&utm_medium=link&utm_source=publishpresent)

<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFQFA5VsAU&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>

- Resize Your Laptop Screen for Workshop Handouts (2 min)<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/Igk5hZUfzN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Step 0: Python Definitions and considerations for beginners

<b>Variable</b>: a variable is a name that stores information. <br>
Examples: `x=2`, `name="Bob"`

<b>Data Type</b>: a grouping of data values that have similar attributes and possible operations. It is possible to have a custom type, in which the attributes are assigned. These can become very intricate and are called <i>objects</i>.<br>
Examples: int `1`, float `0.345`, string `"hello world"`, boolean `True` or `False`, list `[1,2,3]`

<b>Function</b>: A series of operations that changes data or outputs something new. They look like, for example, `len()` a variable with brackets which you can feed information to. <br> Example: `len("hello world")` will return 11 because "hello world" is a string of length 11 (spaces count!).

<b>Method</b>: a method is similar to a function, but it is associated with an object.<br>
Example: if `data = [1,2,3]` and we use a method `data.append(4)` then data would become `[1,2,3,4]`

<b>Argument</b>: An arguments is a variable you "pass" to a function or method. The function or method will use it to perform a transformation or calculation. It goes between the brackets.<br>
Example: From the Function example `len("hello world")`, "hello world" is the argument. From the method example `data.append(4)`, 4 is the argument.

<b>Attribute</b>: Attributes are variables that are associated with an object and tells you information about that object. <br>Example: `dataframe.columns` returns the names of the columns in a dataframe.

<b>Library</b>: libraries are a collection of functions and types created by other people, you can access and use what they have created. <br>
Example: `import pandas` now I would have access to the methods and objects that are packaged together under the name <i>pandas</i>.

<b>Environment</b>: The place in which you run your code. Your variables and libraries are saved here until the environment is cleared. In a jupyter notebook, you have to clear the environment manually.

<b>File paths</b>: file paths are a surprisingly important aspect of programming, it's important to understand how they work. If you don't feel confident about file paths, check out this [File Paths resource by codecademy](https://www.codecademy.com/resources/docs/general/file-paths) <br>
Example: `/home/user/data-analysis/scripts/main.py`

[NEXT STEP: Load and View DataFrame ](1-load-and-view-dataframe.md){: .btn .btn-blue }
