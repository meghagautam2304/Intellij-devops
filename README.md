Eclipse : 
1)After writing the code , right click on project and then team , then share project.\n
2) Right click on the project again , and click on Team, then on Commit , the move your java class file from Unstaged to Staged section .\n
3) Write Commit message and select commit.
4) Right click on project and select team , then click on push branch master and enter user and password. 
5) now refresh the repository you can see the changes made .
6) JENKINS - 
http://localhost:8080
7) click on new item , then select freestyle project 
8) in source code management , enter git 
9) now enter your repository url in it and then move to build steps. 
javac src/Main.java
java -cp src Main
10) Click on build now 

Intellij Idea : 
1)Open Intellij idea and click on new project , select java
2) Name the project and select build system as intellij or maven then create.
3)From top menu click VCS -> Enable Version Control Integration -> Git
4) Right click on project , click on Git and then Add
5)Open Commit window , select all files , type commit message , click on commit 
6) Create repository 
7) Right click on project , go to git -> manage remotes -> add url of repository 
8) Right click -> Git -> push -> login via token 
9)Perform Jenkins steps

