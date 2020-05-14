---
title: "How to Make an R for the Rest of Us Online Course"
author: "David Keyes"
date: "Last Updated Thursday, May 14, 2020 at 7:53 AM (PDT)"
---



# Overview {-}

These are instructions for making an R for the Rest of Us online course. More info will be added soon.

# Curriculum Development

TK

# Course Materials

## GitHub Repo

Each course will have a GitHub repo on the R for the Rest of Us organization account. David will create this and add you to the repo. 

## Project Organization

## Slides

### Slides Template

Slides for R for the Rest of Us courses are made using the [`xaringan` package](https://github.com/yihui/xaringan). 

There is a custom template to use to make slides in the R for the Rest of Us style. You can access this by installing the [`rruthemes` package](https://github.com/rfortherestofus/rruthemes) using the following code:


```r
devtools::install_github("rfortherestofus/rruthemes")
```

Please create a slides directory where all of your slides will live. 

You can create slides as follows:

<iframe src="https://share.getcloudapp.com/P8uEwzAZ?embed=true" width="100%" height="500" style="border:none" frameborder="0" allowtransparency="true" allowfullscreen="true"></iframe>


### Slides Organization

Each lesson should have a My Turn and a Your Turn section. The slide for the My Turn section should have an orange background and the slide for the Your Turn section should have a blue background. 

To do this, add the class `my-turn` and the class `inverse` to your slides as follows:

![](https://p218.p3.n0.cdn.getcloudapp.com/items/7Ku0nre6/Image%202020-05-14%20at%207.39.37%20AM.png?v=87bac6e27ab8c5c303df01a64519ae0d)

# RStudio Setup

## Defaults

Please use default fonts while you are teaching. Pretty as they are, please don't use fonts like [Fira Code](https://benjaminlmoore.wordpress.com/2017/07/19/ligature-fonts-for-r/), as the differences in how they render the assignment operator, for example, can be confusing for newbies.
