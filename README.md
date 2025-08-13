Git is a version control system developed by linux tavold in 2005.
It helps to keep track of changes that are made to source code. It helps to keep track of who made the change. It helps in collaboration.


Github is a source code hosting platform that is owned by microsoft since 2018.
Other source code hosting platform includes Bitbash, Gitlab

concept to be understood includes:
1. Repository: is like a project folder. It makes a hidden file that keep track of all the changes and who made them.
It saves using .git  . It can be classified into:
a. Local repository: it is the project folder that has git initialized in it but its still on our local machine
b. Remote repository: it is like a folder that is existing in the github platform that contains files that is public and can be accessed by anyone.

Configuration
Local Configuration: one user to one repository    git --config user.name "username" git --config user.email "email address
Global Configuration: one user to all repository git --config --global user.name "username"   git --config --global user.email "email address"
System Configuration: all users accessing all repository

2. Stage: is an environment where we keep snapshot of changes
***adding one file to stage env: git add filename.extension
***(adding multiple files to stage env: git add .) or (git add --all)

13th of august 2025
3. Commit
it is used to save stages
Git commit command [git commit -m "message of your choice"] m stands for a message
4. Push
it is like uploading to your remote repository
[git push -u origin branchname]
5. Clone
6. Pull
it is like downloading to your remote repository




**README contains details about what a repository is all about
**Gitignore allows to list important credentials that are not meant to be exposed to the public such as API key, Server IP address
**Repo branch stores different source codes [git branch -M branch-name] 



lets try and edit from the readme and push to see
