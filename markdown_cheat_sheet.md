# 1- Headings
How to give headings in markdown files ?

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

# 2- Block of Words
This is a normal text.
> This is a block quote or a block of special text.
> This is a second line

# 3- Line Break
This is a 40 days long Python course that will be teach by baba Ammar.\
which will  start from today and end after 40 days. \

# 4- Combine Two things
Block of words and heading
> ## Heading 2

# 5- Face of text
**Bold**

*italic*

***bold and italic***

or you can use other symbols too.
underscores(_)

__BOLD__

_ITALIC_

___BOLD AND ITALIC___
# 6- Bullet points/ lists

- DAY-01
- DAY-02
- DAY-03
  - DAY-03(a)
  - DAY-03(b)
    - Sub category 
- DAY-04
- DAY-05

> __using * or + for bullets__
* one
+ two

>__Numbering of lists__

1. Day-01
2. Day-02
3. Day-03
4. Day-04
    1. Day-04(a)
    2. Day_04(b)
5. Day-05

# 7- Line break or page breaks

This is line 1.
---
___
***
This is line 2.

# 8- Links and HyperLinks
[The course of Python by codanics is here](https://codanics.com/courses/python-ka-chilla-for-data-science-40-days-of-python-for-data-science/lesson/markdown-language-crash-course/)

  
[Codanics]:https://codanics.com/courses/python-ka-chilla-for-data-science-40-days-of-python-for-data-science/lesson/markdown-language-crash-course/

The whole course is [here][Codanics]

# 9- Images and figures with links.
To join this course scan the following QR code and join the telegram group:
![QR](qr.png)

> Task: How to comment out a markdown line? and its shortcut?
<!-- Commented line -->
The short cut is Ctrl + /.

A comment will not be printed.

>Online picture
![Codanics](https://codanics.com/wp-content/uploads/2023/09/cropped-250x150-logo.png.webp)

# 10- Adding code or code block

To print a string `print("Codanics")`
`print("Hello World")`

```
x = 5**8
y = 4/6
z = x + y
print(z)
```
> This code will show the color according to python language syntax.

```python
x = 5**8
y = 4/6
z = x + y
print(z)
```
> This code will show the color according to r language syntax.
```r
x = 5**8
y = 4/6
z = x + y
print(z)
```
# 11- Adding Tables

|Species | Petal_length |  Sepal_length|
|:-------:|:--------:|:--------:|
|vergenica | 18.2|  7.7 |
|setosa | 11.2|  3.7 |
|vergenica | 18.2|  7.7 |
|virginica | 17.8|  6.7 |
|versicolor| 16.4|  5.6|

# 12- Table of contents

[1- Heading](#1--headings)\
[2- Block of words/ citation](#2--block-of-words)\
[3- Line break](#3--line-break)\
[4- Combine two things](#4--combine-two-things)\
[5- Face of text](#5--face-of-text)\
[6- Bullet point lists](#6--bullet-points-lists)\
[7- Line break or page break](#7--line-break-or-page-breaks)\
[8- Links and hyperlinks](#8--links-and-hyperlinks)\
[9- Images and figures with links](#9--images-and-figures-with-links)\
[10- Code or code block](#10--adding-code-or-code-block)\
[11- Tables](#11--adding-tables)

# 13- Practise with shortcut keys
**Bold** \
_italic_\
_**Bold and italic**_\
[link](https://codanics.com/courses/python-ka-chilla-for-data-science-40-days-of-python-for-data-science/lesson/markdown-language-crash-course/)

![image](qr.png)

```
code block

```

Column A | Column B | Column C
---------|----------|---------
 A1 | B1 | C1
 A2 | B2 | C2
 A3 | B3 | C3


Column A | Column B | Column C
---------|----------|---------
 A1 | B1 | C1
 A2 | B2 | C2
 A3 | B3 | C3

Here are some key reasons why 📝 Markdown language is important for Jupyter notebooks:

Documentation: Markdown allows you to write documentation and explanations for your code and analysis within the same Jupyter notebook. This helps provide context to your work. 📖

Readability: With formatting options like headings, bold, italics etc., Markdown makes your notes more readable and understandable compared to plain text. 📚

Sharing: When you share Jupyter notebooks, the Markdown formatting is retained. This allows others to easily understand your work without requiring any additional documentation. 📩

Updatability: As you update or refine your code and analysis over time, you can also update the Markdown cells. This keeps your documentation in sync with the latest version. ✅

Platform Support: Major open-source platforms like GitHub, HuggingFace and many others support and recognize Markdown formatting in Jupyter notebooks. This improves portability of your work. 💻

Multi-purpose Usage: Markdown cells are useful for documentation, explanations, visualizations, findings, conclusions and any other text-based contents in your notebooks. ✏️

Lightweight: Markdown syntax is very easy to read and write. It doesn’t require much space or processing power compared to other markup languages. 📝

In summary, Markdown allows seamless integration of documentation with code in Jupyter notebooks, improving readability, reusability and sharing of data science projects. This makes it an essential part of the Jupyter notebook workflow. 📕
