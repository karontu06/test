---
title: "How to push new files to github after closing command prompt"
author: "KCL"
date: "December 7, 2015"
output: html_document
---
#HOW DO YOU ADD NEW FILE TO GITHUB WHEN STARTING A NEW SESSION? AFTER I CLOSED COMMAND PROMPT AND WANT TO START AGAIN?
##Step 1:cd to local repo
cd "/users/karonlewis/desktop/coursera courses/test"
##step 2:
git init
##step 3:
git add READMEpart3.md
##step 4:
git commit -m "how to add to git repo after completely closing CP"
##step 5:don't have to set the origin master again because git already knows what the local repo is linked to
##step 6:
git push -u origin master
