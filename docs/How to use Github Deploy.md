---
layout: default
title: Github deploy
nav_order: 3
---

### Github deploy

For those of you who don't know what Github is, It is a code hosting platform for version control and collaboration. In this document, we will be walking you through how to host your code on Heroku, by pushing it to Github

**1.** Create a new repository in [github](https://github.com)  
![Create a new repository](../assets/images/github-deploy/01_github.png)

***

**2.** Commit and push your code to Github  
    a. ```git init```  
    b. ```git add <_files that you will use_>```
    c. ```git commit -m "first commit"```  
    d. ```git Branch -M main```  
    e. ```git remote add origin <<https://github.com/YOURACCOUNT/PROJECTNAME.git>>```  
    f. ```git push -u origin main```

**If you are struggling to push your code, follow [this link](https://docs.github.com/en/github/importing-your-projects-to-github/adding-an-existing-project-to-github-using-the-command-line) for further instructions.**
#### Now your project is on Github!
***
**Make sure you have already created an app on Heroku! Please access our [Creating a new app](https://github.com/whitebread778/Heroku-user-documentation/blob/gh-pages/docs/Creating-a-new-app.md) documentation if you are having trouble**
**3.** Scroll down to where it says **Deployment Methods.** We will be using this to connect to Github option  
![deployment methods](../assets/images/github-deploy/04_New button.png) 
*** 

**4.** Enter the name of your github repository  
![repository methods](../assets/images/github-deploy/05_repository methods.png)  
***
**5.** After you find the repository, click **connect**. Once you have done that, we are done!


