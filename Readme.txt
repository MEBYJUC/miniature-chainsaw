NodeJS provides the runtime environment to execute the Java Script code from outside the browser

Node Package Manager(npm) can be used for managing and sharing the package for either or angular based project.

npm will be installed along with nodejs

Step1. Install nodejs from nodejs.org 

C:\Users\BYJUC>node --version
v14.17.1

C:\Users\BYJUC>node -v
v14.17.1


To know about npm version any of the following command is fine.
C:\Users\BYJUC>npm --version
7.19.1
C:\Users\BYJUC>npm -v
7.19.1
C:\Users\BYJUC>npm -version
7.19.1


Part -2
Next Step is to install a tool named create-react-app.
This tool will be used to create react application

We can install this as a system level as well as folder level.

We will be installing globally using the below command

here -g stands for global


Create the First ReactJS project

Go to specific folder where you want to create the reactjs application

and type the following command


where demoproject is the name of the project.  name of the react js project name should be small letter


D:\>dir
 Volume in drive D is New Volume
 Volume Serial Number is C279-7757

 Directory of D:\

04-06-2019  12:57 PM    <DIR>          atiksh's_latest_photos(jan_2015)
24-05-2021  03:46 PM    <DIR>          AzureDevOpsData
23-02-2018  11:28 PM             3,264 BUILD_TIENET_BLONLY.bat
05-07-2021  04:32 AM    <DIR>          BYJU
12-07-2021  06:28 PM    <DIR>          demo
03-06-2021  07:48 PM    <DIR>          JavaProjects
11-07-2021  11:25 AM    <DIR>          MyFolder
12-07-2021  06:15 PM    <DIR>          Projects
22-06-2021  03:28 PM    <DIR>          Samples
11-07-2021  11:30 AM    <DIR>          TT
               1 File(s)          3,264 bytes
               9 Dir(s)  84,146,860,032 bytes free

D:\>Cd Projects

D:\Projects>create-react-app  demoproject



Go to project folder

and type

npm start 


D:\Projects>cd demoproject

D:\Projects\demoproject>npm start


Application will get started in specificed path



How to  ?
Create and publish to GitHub Repository?
First go to github
https://github.com/

and create a repository. In this example we are using existing repository


https://github.com/MEBYJUC/miniature-chainsaw.git


Go to the project folder, open the command prompt

before we continue further we need to remove every git releated files in this folder. for that type the following command

D:\Projects\demoproject>rd .git /S/Q

D:\Projects\demoproject>


initiate a git repository under local repository. for that you type git init

D:\Projects\demoproject>git init
Initialized empty Git repository in D:/Projects/demoproject/.git/

so .git file will be created as hiddent file

to see that hiddent file in command prompt type the following

D:\Projects\demoproject>attrib -s -h -r /s /d *.*


we add every thing by adding  git add command


next step is we need to commit this file for that we need to add  git commit command

D:\Projects\demoproject>git commit -m "My First Commit "



So we created GitHub reposiory which is empty for the moment and  we create local git repository
next we need to configure these two with each other

To that we add git remote add origin  <<github URL>>


https://github.com/MEBYJUC/miniature-chainsaw.git

D:\Projects\demoproject>git remote add origin https://github.com/MEBYJUC/miniature-chainsaw.git

D:\Projects\demoproject>git push  -u origin master
















