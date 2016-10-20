GitHub is a shared web hosting service for software development projects that use Git version sistempengontrol. GitHub offers both free and commercial packages for open source projects and launched since tahun2008. According to a survey of Git users in 2009, GitHub is the popular Git hosting site.
how to upload files to the repository GitHub we have in windows (I use Windows 7 would be easier if you use linux).

- A device in use

1. GitHub account, to upload a project to GitHub course, we must have the GitHub account, how to create an account on the website directly https://github.com then register.

2. Software Git, For this software you can download for free in http://git-scm.com/, if already downloaded simply install.


Once we have the GitHub account and software mengistall git then we can directly upload our project.

- Make the repository on GitHub repo by clicking on the icon "Create new repository".

- Then name the repository and give a description for the repository that we make, if necessary, and then setting public / private, if public means it can be accessed by everyone, then check the "initialize this repository with a README" and add the category repository JILA need.

- Then click on "create repository".

- If the repository is established, you will be given the keys akases form of HTTP / SSH, which we will use for remote GIT repository of software. Suppose I had a key HTTP http://github.com/username/repository.git

- Once you have successfully membiat repository now right click on the project folder to be uploaded.

- Right click on the project click "Git Bash".

- This will bring up a command prompt / CMD

- If you are a first time receipts GIT software, you should configure your username and email first.
Type

**Git config --global user.name "username"**
 
**Git config --global user.email "isi_dengan_email"**
 
- After configuring the username and email, now we do initiation, typewriting
 git init
 
- Then we add all the files in the folder of our project, typing

 **(Git add * )**
 
- Then we make her commit project, for example here I love commit "version 1.0.0", typewriting

**Git commit -m "version 1.0.0"**
 
- After we make him commit to the project, we now remote repository that we created earlier, of course, we use the existing HTTP key in the last repository, if ane right before her http://github.com/username/repository.git example, typing

**Git remote add origin http://github.com/username/repository.git**
 
- Having to remote repository we are now, we pull her project, typewriting

**Git pull origin master**
 
- Recently we send our project to our repository, typing

**Git push origin master**
 
Usually when we are typing a command of this push, we will be asked username and password and need to be noticed for his password when we his usual typing the password on the command prompt it does not display any character.
