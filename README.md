# GitHub
VmTutes Git-Hub
GitHub
======

1. What is Github
2. Overview of github
3. Github account creation
4. Difference between git & github
5. Difference with other tools
6. create repo in local machine and push to github
7. Clone existing repos from github
8. Managing tags remotely
9. fetch and pull
10. Workflow
11. Forking Repos
12. pull request
13. Deleting and renaming GitHub Repos

Alternatives
------------
1. gitHub
2. Bitbucket
3. Gitlab
...etc

GitHub
------
GitHub is a website and cloud-based service that helps developers store and manage their code, 
as well as track and control changes to their code.
@ is a website to upload repositories online
@ Provides backup remotely

Github account creation
-----------------------
Sign up https://github.com/
Note :- how to create acc, steps are in "github installation folder" in google drive 

Difference between git & github
-------------------------------
1. git is a tool  <--> github is a website (github.com)
2. git is Command line interface(CLI) <--> github is Graphical user interface(GUI) 
3. we can't view data in bare repo  <--> but we can view & do all actions in bare repo 
4. bare is bare only here  <--> but, bare repo you can convert into non-bare here   
5. here we are creating non-bare by cloning bare repo  <--> but, directly we can create/init non-bare                                             
6. local  <--> remotely  

GitHub PAT:- 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

Difference with other tools
---------------------------
	
	@ it Provides nice visual interface to repo
	@ makes user collaboration easier
        @ security
        @ 24/7 support
        @ user friendly
        @ flexibility
        @ it provides backup for repo's
        @ microsoft take over

1. create repo in local machine and push to github
--------------------------------------------------
 
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/VmTutes/hello.git
git push -u origin master
username:-
password:- PAT Token

Note:- to generate PAT token go to settings/developer settings/personal access token/classic/generate newtoken

2. Clone existing repos from github
-----------------------------------
- clone existing repository from github to your local machine 
    >> git clone https://github.com/VmTutes/Vinodh-Machireddy-Tutorials.git

- change some data and add, commit
- git push (or) git push origin master

Managing tags remotely
----------------------
to create tag
  >> git tag <tag_name>

push tags from local repo to github repo
  >> git push origin --tags

to delete tags remotely in github
  >> git push origin -d <tag_name>

to delete tags locally
  >> git tag -d <tag_name>

fetch and pull differences
--------------------------
pull = fetch + merge

fetch :- it just download the changes to local machine but it will not integerate.
merge :- it integrates to local repo of git

workflow:-
=========
	     |		Add	       |	Commit	       |			      |	 	
	     |------------------------>|---------------------->| 			      |  		       			      
	     |----------------Commit -a ---------------------->|	  git push            |
	     |			       |		       |----------------------------->|
	Working Dir		     Index		Commiting Area 		      Remote Repository(GitHub)
	(work space)  	  	   (Staging)	    	    (HEAD)			      | 	
	     |			       |		       |<----------git fetch----------|
	     |<-------------------Merge------------------------|			      |	
	     |			       |		       |			      |	
	     |<----------------------------------Pull-----------------------------------------|
	     |<--------------------diff HEAD------------------>|			      |
	     |<----------diff--------->|

Forking Repos
-------------
>> cloning others public repos into our account to contribute changes.

Pullrequest
-----------
![Pullrequest](https://user-images.githubusercontent.com/30006273/205886521-4c8d59af-7e32-4d4f-ae6c-657cb7b3d8fe.png)



Deleting and renaming GitHub Repos
----------------------------------
go to repository settings page and rename, delete.
https://github.com/VmTutes/Vinodh-Machireddy-Tutorials/settings
	

   						   =========THE END=======
			    VmTutes, +91-7204143230(WhatsApp/Call), Email:- Vinodh-Machireddy@VmTutes.com



