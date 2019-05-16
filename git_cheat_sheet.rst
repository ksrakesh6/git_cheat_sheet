#######################################

			GIT CHEATSHEET

#######################################

# To check the  version of git 

git  --version 

# To set up  the configuration  Git  

git config --global user.name "USERNAME"
git config --global  user.email "em@iladdress"

git config --list 

# HELP 

git help <verb>
git <verb> --help 

# To initialize a repository from existing Code

git init 

# To get untracked/modified  status  of Git  

git status

# To ignore the files that available in the folder which is specific to development preferences 

1. Create  a   file with name '.gitignore'
2. Add the entries in the .gitignore file
   eg :  *.pyc
   
#  To add files to staging area

git add  -A  
git add  <filename>

# To remove file from staging Area

git reset
git  reset <filename>

# To commit files in git 

git commit -m  "Initial Commit"

# To get log from the git 

git log 


# Clonning a remote repository

git clone <url to clone > <folder to cone>


# To view remote information 

git remote -v 
git branch -a 

# To view the changes in the code

git diff 

# To add files in git remote directory 

git pull origin master
git push origin master  