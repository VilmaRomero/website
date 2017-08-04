---
title: 'Day 2 - Reproducible Research using R Studio'
author: ''
date: '2017-08-24'
weight: 3
publishDate: '2017-08-04'
slug: day-2-Rstudio
categories: [intro]
tags: [rstudio, reproducible_research]
draft: false
---

# Introduction
In this lab you will learn to write a document using R markdown, integrate live R code into a literate statistical program, compile R markdown documents using knitr and related tools, and organize a data analysis so that it is reproducible and accessible to others.

## Why Reproducible Research? 

From the Coursera [Reproducible research](https://www.coursera.org/course/repdata) course description: Reproducible research is the idea that data analyses, and more generally, scientific claims, are published with their data and software code so that others may verify the findings and build upon them.  The need for reproducibility is increasing dramatically as data analyses become more complex, involving larger datasets and more sophisticated computations. Reproducibility allows for people to focus on the actual content of a data analysis, rather than on superficial details reported in a written summary. In addition, reproducibility makes an analysis more useful to others because the data and code that actually conducted the analysis are available. This course will focus on literate statistical analysis tools which allow one to publish data analyses in a single document that allows others to easily execute the same analysis to obtain the same results.

## RR in current day science
Here are some examples and articles that demonstrate why reproducible research is important. 

* [Simply Statistics](http://simplystatistics.org/2014/06/06/the-real-reason-reproducible-research-is-important/) - The real reason reproducible research is important.
* Special articles in [Nature](http://www.nature.com/news/reproducibility-1.17552) that talk about the need to share code and reproducibility in the sciences. 
* The spreadsheet error and austerity - as seen through [The Colbert Report](http://thecolbertreport.cc.com/videos/kbgnf0/austerity-s-spreadsheet-error---thomas-herndon)'s eyes. Moral of this story: ask for the data and question results that look too good to be true. Even graduate students can find serious errors!


### Additional Resources
If you are still struggling with R Markdown after you complete Lab 1, follow along with [this](https://www.youtube.com/watch?v=DNS7i2m4sB0) tutorial by Roger Peng. Reproduce what he does in the video on your own machine. 
 
----- 

## On Your Own

1. Right click this link [Lab 1.Rmd](/labs/Lab1.Rmd) link and **Save As** (or Save Link As) to download the RMarkdown file. Save this in your class folder. 
2. Double click to open this file in R Studio
  - You might have to tell your computer what program to use. 
3. Click the **knit button** at the top to this file to HTML. 
    - Don't have a **knit** button? Have you installed the `rmarkdown` package yet? `install.packages("rmarkdown")`. 
4. Look at each piece of the output around problem 0. Mentally match each piece of output with the corresponding section in the RMD file. 
5. This provides a homework template for you to use to write your assignment. Write your answers directly into this document. 
6. Submit the **RMD** file via BBLearn before the due date. I will knit the file on my machine and grade the result. Make sure it looks good before turning it in!

### Want to learn more Markdown syntax? 
* A short video from [The Data Scientist's Toolbox](https://www.youtube.com/watch?v=Nc0CS0nX-M4) from the Coursera course.
* R Studio [cheat sheet]()
* R Studio [video tutorial]