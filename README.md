# test
# adding this read me to github test repository
# steps
>> First, I created empty repository on GITHUB. I didnot initialize with a Readme
>>It gave me the following code to initialize with a readme
##need to cd to my local directory before doing anything below.
1-echo "# test" >> README.md 
##first line: adds a new readme file to my computers respository
2-git init
##second line starts up github in command prompt
3-git add README.md
##third line tells git we want to add README.md file; use "git add ." to add all files located in local repo to git repo
4-git commit -m "first commit"
##fourth line tells git we want to commit the files added in the previous statement
5-git remote add origin https://github.com/karontu06/test.git
##fifth line tells git where we want these files to go
6-git push -u origin master
##sixth pushes the files to the github repo "origin master"


