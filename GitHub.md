# Basic 

<span style="color : yellow"></span>


Git = (Software )it is a version control system project ki puri ki puri history track krta he </br>
Free & Opensource </br>
Fast & Scalable 

GitHub = (website) that allows developer to store and manage thier code using Git 
<!--! https://github.com -->

changes ==> Commit kehte he 

# CD (Change Directory)
CD = directory change krne ke liye ya folder me jane ke liye 
<span style="color : yellow">
 cd Folder_Name 
</span>

# mkdir (make directory)
### mkdir = new folder ya directory banane ke liye 
<span style="color : yellow">
mkdir {Name} </span>


# ls (list Files)
ls = files list krne ke liye 
<span style="color : yellow">
ls</span>


# Configuring Git 
matlab batana padega ki konse account me change krne jaa rha ----------

to set name ..
<span style="color : yellow">
git config --global user.name "My_Name" 
</span>


to set email ..
<span style="color : yellow">
git config --global user.email "My_Email" 
</span>


to check .. 
<span style="color : yellow">
git config --list 
</span>

# CLONE & STATUS 

### Clone = (Copy krne ke liye) cloning repo on our local Machine ( laptop , personal computer ) 
 => Outsource se folder ko copy ya clone krne ke liye 
<span style="color : yellow">
git clone <-some link->
</span>

### Status = code ka status batati he 
<span style="color : yellow">
git status
</span>

untracked = new file jisko Git track nhi kr rha he
modified = changed 
staged = file is ready to be committed 
unmodified = unChanged 



# Add & Commit 
### add = adds new or changed file in your working directory to the Git Staging area (engagement process)
<span style="color : yellow">
git add <-file name-> 
</span>

### commit = It is the record of change (Wedding Process)
<span style="color : yellow">
git commit -m "Some_Massege" </span>

# Push Command 
### Push = Local System pe jo changes he usko Github pe push kr dete he (Upload local repo content to remote repo/github )
<span style="color : yellow">
git push origin main
</span>


# init Command 
### init = Used to create new Git repo 
<span style="color : yellow">
git init </span>

#### git remote add origin <-link->
#### git remote -v

# Branch 
#### Main project ki multiple branch hoti he As a Tree 
### To change branch name => 
<span style="color : yellow">
git branch -M Name
</span>


# WorkFlow 
### github Rep ---> clone ---> changes ----> add ---> commit ----> push 


# Branches 

to check branch 
<span style="color : yellow"> git branch</span>
to rename branch 
<span style="color : yellow"> git branch -M main</span>
to navigate
<span style="color : yellow">git checkout <-branch_name-> </span>
to create new Branch
<span style="color : yellow"> git checkout -b <-branch_name-> </span>
to delete branch
<span style="color : yellow"> gid branch -d <-branch_name-> </span>


### Merge Brach / Merge Code </>
##### Way 1 (Through git / command line)
( to compare commit , branches , files & more )
<span style="color : yellow">
git diff <-branch_name-> 
</span>

( to merge 2 branches )
<span style="color : yellow">
git merge <-branch_name-> 
</span>

### To remote changes to main 
###### Github -------> Local Machine
<span style="color : yellow">
git pull origin main </span>
used to fetch and download content from a remote repo and immediately update the local repo to match that content 


##### Way 2 (Through Pull Request)
###### It lets you tell other about changes you've pushed to a branch in a repository on GitHub

### Resoving Merge Conflict 
##### An event that takes place when Git is unable to automatically resolve hte differences in code between two commits

<span style="color : orangered">
manually btana padta he konsa change rakhna he </span>

### Undo Changes 
wapas usi stage pe aane ke liye 
<span style="color : yellow">
git reset <-file_name-> / git reset </span>



# Fork 
### fork = rough copy of any project 


