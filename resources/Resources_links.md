---
title: "Helpful R Resources"
output: 
  html_document: 
    keep_md: yes
    toc: yes
    toc_depth: 2
    toc_float: 
      collapsed: false
---




# (updated: 2022-05-18)

***  

# Troubleshooting help  

+  __[Where to get help with your R question?](https://masalmon.eu/2018/07/22/wheretogethelp/)__ - from Maelle Salmon's blog  

+  __[Writing the perfect question](https://codeblog.jonskeet.uk/2010/08/29/writing-the-perfect-question/)__ - from Jon Skeet's coding blog  

***

# Intro material  

+  __[R basics, workspace and working directory, RStudio projects](https://stat545.com/r-basics.html)__ - from STAT 545  

+  __[What They Forgot to Teach You About R](https://whattheyforgot.org/)__ - workshop materials by Jenny Bryan and Jim Hester
   

***

# Extra Resources  

+  __[RStudio cheat sheets](https://www.rstudio.com/resources/cheatsheets/)__ - seriously, check them out  

+  __[RStudio keyboard shortcuts](https://support.rstudio.com/hc/en-us/articles/200711853-Keyboard-Shortcuts)__  

    Some of my favorites are:  

    +  `Ctrl` + `Enter`: run current line or selected code  
    +  `Ctrl` + `-`:  the assignment operator (`<-`)  
    +  `Ctrl` + `Shift` + `c`: comment all selected lines (insert `#` in front)  
    +  `Ctrl` + `i`: re-indent selected code
    +  `Ctrl` + `Alt` + `i`: insert a code chunk into RMarkdown file  
    +  `F2`: shows code used by function  


+  __[RStudio webinars](https://resources.rstudio.com/webinars)__  Several helpful webinars and presentations from past _rstudio::conf_ meetings.  


## Additional `ggplot2` Resources

Thomas Lin Pederson ([@thomasp85](https://twitter.com/thomasp85)) is a software engineer at RStudio and co-author of the `ggplot2` package (among other things).
In 2020, he gave an impromptu workshop (2020-03-24) for beginner/intermediate R users:  

+  **[Part One (~2.5 hours)](https://www.youtube.com/watch?v=h29g21z0a68)** is focused on the grammar of graphics and theory behind `ggplot2`
+  **[Part Two (~2 hours)](https://www.youtube.com/watch?v=0m4yywqNPVY)** discusses extension packages to the `ggplot2` universe (`gganimate` and `patchwork` for example)
+  His materials are also available on [GitHub](https://github.com/thomasp85/ggplot2_workshop )


## Version Control: [Git](https://git-scm.com) and [GitHub](https://github.com)

+  __[GitHub tutorial and resources from Karl Broman](https://kbroman.org/github_tutorial/)__

*see the "Free Online Books - Version Control (Git and Github)" section below for books on this topic.*

***

# Communities  

+  __[RStudio Community Forums](https://community.rstudio.com/)__  

+  __[R4DS community](https://www.rfordatasci.com/)__ - Be sure to join the slack channel  

+  __[ROpenSci](https://ropensci.org/community/)__    

+  __[Tidy Tuesday](https://github.com/rfordatascience/tidytuesday)__  
+  __[Ecology in R Facebook Group](https://www.facebook.com/groups/ecologyinr/)__


***

# Free Online R Books  

Some more specialized than others  

## R and the `tidyverse` Generally  

+  __[R For Data Science](https://r4ds.had.co.nz/)__ - by Hadley Wickham and Garrett Grolemund; 2nd edition in progress  

+  __[Hands-On Programming with R](https://rstudio-education.github.io/hopr/)__ - by Garrett Grolemund  

+  __[Getting used to R, RStudio, and R Markdown](https://bookdown.org/chesterismay/rbasics/)__ - by Chester Ismay  

+  __[ModernDive: Statistical Inference via Data Science](https://moderndive.com/index.html)__ - by Chester Ismay and Albert Y. Kim. Don't let the title scare you; there's a lot in here about R and RStudio generally.    

+  __[Advanced R](https://adv-r.hadley.nz/)__ , 2nd edition - by Hadley Wickham      

+  __[R Packages](http://r-pkgs.org)__ , 2nd edition in progress - by Hadley Wickham and Jenny Bryan    

## Data Viz  

+  __[Data Visualization: A Practical Introduction](http://socviz.co/)__ - by Kieran Healy. Also a good intro to the `ggplot2` package; learn by doing.    

+  __[Fundamentals of Data Visualization](https://serialmentor.com/dataviz/)__ - by Claus O. Wilke


## R Markdown  

+  __[R Markdown: The Definitive Guide](https://bookdown.org/yihui/rmarkdown/)__ - by Yihui Xie, J.J. Allaire, and Garrett Grolemund  

+  __[R Markdown Cookbook](https://bookdown.org/yihui/rmarkdown-cookbook/)__ - by Yihui Xie, Christophe Dervieux, and Emily Riederer  


## Geospatial Data  

+  __[Geocomputation with R](https://geocompr.robinlovelace.net/)__ - by Robin Lovelace, Jakub Nowosad, and Jannes Muenchow  

+  __[Spatial Data Science](http://r-spatial.org/book)__ - by Edzer Pebesma and Roger Bivand; in progress  


## Version Control (Git and Github)  

+  __[Happy Git with R](http://happygitwithr.com)__ - by Jenny Bryan  

***

# Statistics using R (not just books)  

## General stats  

+  Book: __[Learning Statistics with R](https://learningstatisticswithr.com)__ - by Danielle Navarro. Aimed at psychology researchers but has great motivating examples of why we even use statistics in the first place. Includes lots of clearly explained, worked examples using R code.  

+  Book: __[ModernDive: Statistical Inference via Data Science](https://moderndive.com/index.html)__ - by Chester Ismay and Albert Y. Kim. 

## Ecological, Environmental, and/or Water Resources Statistics  

+  Book: __[Statistical Methods in Water Resources, 2nd ed.](https://pubs.er.usgs.gov/publication/tm4A3)__ - by Dennis R. Helsel, Robert M. Hirsch, Karen R. Ryberg, Stacey A. Archfield, and Edward J. Gilroy. Amazing reference for water quality stats and code.   

+  Workshop: __[Introduction to Multivariate Data Analysis using vegan](https://github.com/gavinsimpson/intro-vegan-webinar-july-2020)__ - by Gavin Simpson. `vegan` is an extremely popular package for running community analyses for ecology. Link is to GitHub repository with materials; that GitHub page links to the recording on YouTube.  

+  Workshop: __[Advanced Community Ecological Data Analysis using vegan](https://github.com/gavinsimpson/advanced-vegan-webinar-july-2020)__ - by Gavin Simpson. Link is to GitHub repository with materials; that GitHub page links to the recording on YouTube.  

+  Tutorial: __[GAMs in R](https://noamross.github.io/gams-in-r-course/)__ - by Noam Ross. Helpful interactive overview of Generalized Additive Models, which are becoming popular in ecology and water resources analyses.  

+  Class notes: __[Statistics for Environmental Science](https://sakai.unc.edu/access/content/group/2842013b-58f5-4453-aa8d-3e01bacbfc3d/public/Ecol562_Spring2012/index.html)__ - lecture notes include a lot of useful topics, including GAMs, survival analysis, spatial and spatio-temporal stats, regression trees.  

+  Class notes: __[Statistical Methods in Ecology](https://sakai.unc.edu/access/content/group/3d1eb92e-7848-4f55-90c3-7c72a54e7e43/public/index.html)__ - same professor as above. More introductory.  

### Helpful books to get but unfortunately not freely available  

Links lead to the publisher's page.  

+  Gotelli and Ellison, 2012. __[A Primer of Ecological Statistics, 2nd edition](https://global.oup.com/academic/product/a-primer-of-ecological-statistics-9781605350646?cc=us&lang=en&)__  

+  McCune, Grace, and Urban, 2002. __[Analysis of Ecological Communities](https://www.wildblueberrymedia.net/analysis-of-ecological-communities)__


 

 

