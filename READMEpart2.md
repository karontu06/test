---
title: "READMEpart2"
author: "KCL"
date: "December 7, 2015"
output: html_document
---

```{r}
summary(cars)
```

You can also embed plots, for example:

```{r, echo=FALSE}
plot(cars)
```

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.

#ADDING ADDITIONAL FILES TO THE SAME GITHUB REPOSITORY, WHILE YOU ARE IN IT STILL
##STEP 1:
Create your new file and save to your local repository
##STEP 2: git add the new files you want tranferred to repo
git add READMEpart2.md/ or git add .
##STEP 3: git commit -m to tell git you want the files in the add queue committed to the github repo
git commit -m "second commit with new file"
##STEP 4: since, origin master already set, can bypass setting it with git remote add origin; push files to github
git push -u origin master  
