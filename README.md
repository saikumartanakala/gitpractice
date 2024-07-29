###############################################################################################

**LINUX**
root directory--->/
homw directory--->~
[ec2-user@ip=182-23-46-51 ~]$
user name    ip address
date-->Mon Jul 29 09:25:56 UTC 2024
ctrl + d --->logout the linux
clear--->clear the screen
history-->to show the recent used commands
ls--> to list the files
ls -a---> to list all files
ls -ll--->to show the full information of all files(ll means letter l)
ls -11---->to show the all the file names(11 means one one)
ls -al----> to show hidden files
cd->> change one location to other location
cd ..------>go back to one step

 df-h ---->Displays free space on mounted systems
 df-i --->Displays free inodes on filesystems
 fdisk-l ---->Shows disk partitions,sizes,and types




***How to setup git in ubuntu
apt install git -y
check the git is installed--->git -v
create directory--->mkdir gitfiles
clone the git repo in server--->git clone git repo url
user name---->saikumartanakala
password--->****************
list the files---->ls
chnage directory---->cd directory name
list the files-----> ls
create file---->touch filename
add the content in files--->vi filename 
content is added 
save the file --->:wq!
view the file on server---->cat filename
chack the any committed occur---> git status
send a stagging area---> git add . filename
commit the chnages--->git commit -m "give the comment"
send to git server--->git push origin main
user name---->saikumartanakala
password--->****************
which branch i am working and give the list of branches--->>git branch
create branch----> git branch feature1
change one branch to other branch--->git checkout feature1

** PROCESS OF CONFLICT IN GIT**
In main branch select one file and edit the one line --->click commit changes
In feature2 same process--->commit chnages
NOT WORKING PROPERLY


** PROCESS OF CONFLICT IN UBUNTU**

git branch
main
vi filename
edit one line
git add .
git commit -m "comment"
git checkout feature2
vi filename
edit same line
git add .
git commit -m "comment"

git merge feature1
conflict raised
git mergetool
again click enter
choose the lines you want
remove unwanted lines click dd to remove entire line
:wq
:wq
:wq
ls
you find the filename.orig file
rm filename.orig  
git add .
git reset
git add .
git commit -m "comment"
git push origin main
user name---->saikumartanakala
password--->****************
enter
git log
ctrl + z
***




