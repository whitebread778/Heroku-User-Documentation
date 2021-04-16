---
layout: default
title: Creating an app using github deploy
nav_order: 1
---

### Creating an app using github deploy

For those of you who don't know what Github is, It is a code hosting platform for version control and collaboration. In this document, we will be walking you through how to host your code on Heroku, by pushing it to Github

1. Create a new repository in [github](https://github.com)  
![Create a new repository](https://github.com/whitebread778/Heroku-user-documentation/blob/gh-pages/assets/images/github-deploy/01_github.png)

***

2. Commit and push your code to Github  
    a.  git init  
    b. git add <_files that you will use_>  
    c.  git commit -m "first commit"  
    d. git Branch -M main  
    e.  git remote add origin < <https://github.com/YOURACCOUNT/PROJECTNAME.git>>  
    f.  git push -u origin main 

**If you are struggling to push your code, follow [this link](https://docs.github.com/en/github/importing-your-projects-to-github/adding-an-existing-project-to-github-using-the-command-line) for further instructions.**
#### Now your project is on Github!
***

3. Open Heroku

***
4. Click **New**

![New button](https://github.com/whitebread778/Heroku-user-documentation/blob/gh-pages/assets/images/github-deploy/02_Create%20new%20app.png)  
*** 
5. Click **Create new app**  
![Create new app](https://github.com/whitebread778/Heroku-user-documentation/blob/gh-pages/assets/images/github-deploy/03_deployment%20methods.png)
***
6. Enter the name of your app, then **Create the app**  
***
7. Scroll down to where it says **Deployment Methods.** We will be using the connect to Github option  
![deployment methods](https://github.com/whitebread778/Heroku-user-documentation/blob/gh-pages/assets/images/github-deploy/04_New%20button.png) 
*** 
8. Enter the name of your github repository  
![repository methods](https://github.com/whitebread778/Heroku-user-documentation/blob/gh-pages/assets/images/github-deploy/05_repository%20methods.png)  
***
9. After you find the repository, click **connect**. Once you have done that, we are done!


