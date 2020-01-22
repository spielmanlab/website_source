+++
# Date this page was created.
date = "2019-08-31"


# Project title.
title = "Data Science for Biologists"

# Project summary to display on homepage.
summary = "Materials for Spring 2020 BIOL01301."

url = "courses/datascience_for_biologists/"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["All Courses", "Rowan Courses"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

reading_time= false  # Show estimated reading time?
share= false  # Show social sharing links?
profile=false  # Show author profile?
commentable= false  # Allow visitors to comment? Supported by the Page, Post, and Docs content types.
editable= false  # Allow visitors to edit the page? Supported by the Page, Post, and Docs content types.

+++

This website contains all materials used in BIOL 01301 Spring 2020 at Rowan University with Dr. Spielman. This course meets Monday 12:30-1:45 in SCI 239, Wednesday 12:30-1:45 in SCI 226, and Thursday 11-1:45 in SCI 239. 

**All grading and assignment submissions (unless otherwise stated) will be hosted on [Blackboard](https://rowan.blackboard.com/), but course materials will be posted on this site.**

<br>

## Key documents and links

+ [**Download the course syllabus**](./Spring2020_Spielman_Syllabus_DataScience.pdf). This document contains all course policies. *When in doubt, check here first*.

+ [**Download the regrade form**](./regrade_policy.docx). This form may be used to request a formal regrade on an assignment or exam. Please consult this document for instructions.

+ **Student Visiting Hours** will be held *Wednesday and Thursday in Science Hall 201D from 2:30 - 4 pm*. You do not need to make an appointment. To speak with me one-on-one with a guarantee of privacy, please set up an appointment with me via [email](mailto:spielman@rowan.edu). 
    
+ **Assigments** are always due **one hour before class at 10 am, unless otherwise stated** (most assignments are due on lab days). If you submit your assignment within an hour of class, you will automatically be deducted 10%.  _Late assignments will not be accepted without prior permission, which you can get by contacting me as needed!!_
 
+ **You are expected to bring your laptop to every class.** If you do not have a laptop or tablet with external keyboard/mouse, one will be provided for you.

+ Join the class RStudio Cloud Space [here](https://rstudio.cloud/spaces/44379/join?access_code=W5xszVLeEv3YK05165JOaapp5N6cLuzuoWqwj30a) 

<br>

## Online Books and Resources

+ [Fundamentals of Data Visualization](https://serialmentor.com/dataviz/) by Claus O. Wilke
+ [R for Data Science](https://r4ds.had.co.nz/) by Garrett Grolemund and Hadley Wickham
+ [Data Visualization: A practical Introduction](https://socviz.co/) by Kieran Healy
+ [`tidyverse` homepage, official documentation, and cheatsheets](https://www.tidyverse.org/)
+ [Calling Bullshit Course Website](https://callingbullshit.org/) by Carl Bergstrom and Jevin West

<br>

## Class Schedule and Materials

> Materials are subject to change up until the day of class based on student progress. Any change in deadlines will only be to _postpone_.


| No. | Day/Date |<div style="width:250px">Topic and materials</div> | Background Reading         | Assignment DUE
------|----------|--------------------------------------------------|-----------------------------|--------------------
1     | W 1/22   | Introduction/Syllabus Day | None | None
2     | R 1/23   | [Introduction to R and RStudio](http://htmlpreview.github.io/?https://github.com/sjspielman/datascience_for_biologists/blob/master/01-introduction-base-R.html)| None | None
3     | M 1/27   | Types of data and distributions  | Two blog posts on types of data: <br> 1. [Towards Data Science](https://towardsdatascience.com/data-types-in-statistics-347e152e8bee) <br> 2. [Scary Scientist](http://scaryscientist.blogspot.com/2015/02/classification-of-data-types.html)   | None
4     | W 1/29   | Introduction to data visualization | Read chapters 5, 6, 7, and 10 from "Fundamentals of Data Visualization"
5     | R 1/30   | [Introduction to `ggplot2`](http://htmlpreview.github.io/?https://github.com/sjspielman/datascience_for_biologists/blob/master/02-introduction-ggplot2.html)   | None |
6     | M 2/3    | Communicating with (in)effective visualizations | Watch ["Lecture 6: Data Visualization" Videos](https://callingbullshit.org/videos.html) | Bring **two** visualizations to class, printed in color!  
7     | W 2/5    | [Introduction to RMarkdown](http://htmlpreview.github.io/?https://github.com/sjspielman/datascience_for_biologists/blob/master/03-introduction-rmarkdown.html) | None | None
8     | R 2/6    | [More practice with `ggplot2`](http://htmlpreview.github.io/?https://github.com/sjspielman/datascience_for_biologists/blob/master/04-more-ggplot2.html) | Read chapter 21 from "Fundamentals of Data Visualization" | `Introduction to ggplot2` assignment due on Blackboard as an R script.
9     | M 2/10   | [Manipulating data with `dplyr` I] | Look over [`dplyr` vignette](https://dplyr.tidyverse.org/articles/dplyr.html) | None
10    | W 2/12   | Manipulating data with `dplyr` II | None | None
11    | R 2/13   | [Data manipulation and visualization] <!-- CO2 dataset? --> | None | `More practice with ggplot2` assignment due on Blackboard as an Rmd file.
12    | M 2/17   | Manipulating data with `dplyr` III
13    | W 2/19   | Best-practices, debugging, and other hot topics
14    | R 2/20   | [Debugging code]
15    | M 2/24   | Introduction to Tidy data principles | Read [Tidy Data Paper](https://vita.had.co.nz/papers/tidy-data.pdf) | `Data manipulation and visualization` assignment due on Blackboard as an Rmd file.
16    | W 2/26   | Tidying data with `tidyr` | Look over [`tidyr` vignette](https://tidyr.tidyverse.org/articles/tidy-data.html)
17    | R 2/27   | [From untidy to tidy: Tidying, manipulating, and visualizing] | None | `Debugging` assignment due on Blackboard
18    | M 3/2    | Introduction to Version Control with GitHub
19    | W 3/4    | Practice with GitHub
20    | R 3/5    | [Conducting reproducible analyses] | None | `From untidy to tidy` assignment due on Blackboard
21    | M 3/9    | Writing functions in R | None | None
22    | W 3/11   | Using and building packages in R | None | None
23    | R 3/12   | [Making an R package] | None | **Midterm Project due on Blackboard at noon**
--    | M 3/16 - F 3/20 | **SPRING BREAK!** | None |  None  
24    | M 3/23  | Introduction to hypothesis tests and modeling
25    | W 3/25  | Permutation and randomization testing
26    | R 3/26  | [Analyzing data with permutation tests]
27    | M 3/29  | Linear modeling I 
28    | W 4/1   | Linear modeling II
29    | R 4/2   | [Analyzing data with linear models]
30    | M 4/6   | Many models and multiple testing corrections
31    | W 4/8   | Binary classification and logistic regression
32    | R 4/9   | [Analyzing data with logistic regression]
33    | M 4/13  | Strategies for model evaluation and selection I
34    | W 4/15  | Strategies for model evaluation and selection II
35    | R 4/16  | [Evaluating models]
36    | M 4/20  | Classification: Approaches to clustering data
37    | W 4/22  | Classification: Approaches to dimension reduction
38    | R 4/23  | [Clustering and dimension reduction Lab]
39    | M 4/27  | Communicating your science
40    | W 4/29  | *Open day to work on final project*
--    | W 5/6   | **Final project due and "presentations" party**