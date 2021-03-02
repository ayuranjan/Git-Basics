# Git-Basics
Basic Git Commands


1. git clone ____ // get my own copy of a repository

2. git add --all  // after adding or changing any files in my repository

3. git commit -m "I made some changes, why?"

4. git push // to send my local code to the central repository

5. git pull // pull code to local system from central repository


STEPS to Clone a repository :-
1. Go to command terminal 
2. cd path where you want that file
3. Open Github's repository which you want to clone .
4. Click on Clone button
5. Link will get displayed , click on copy button 
6. Come back to command line
7. git clone link(copy) 
8.Enter 

Steps to push a file in a  existing  repository:-
1. On your computer, move the file you'd like to upload to GitHub into the local directory that was created when you cloned the repository.
2.Open Terminal.
3.Change the current working directory to your local repository.
4.  git add --all
5. git commit -m "Add existing file"
6.git push 



Steps to push a file into a new repository :- 
1. go to terminal and change directory to the path of the project/folder 
2.  type git init - this is to make a local repository 
3. type git add . - to add all files 
4. optional -  type git status to check the file to be commited  
5. type git commit -m "first commit" -- the message can be anything 
6. copy the repository url from github 
7. type git remote add origin url 
8. type git push -u origin master
9. Done 
