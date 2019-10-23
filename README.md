# HELPBOX:fish:
Here you can find information on how to add and get projects from this repository


## First of all install [Github Console](https://git-scm.com/download/win) or [Github Desktop](https://desktop.github.com/) on your computer

In this short guide we will show you how to use it in console.


### To clone a project
> First of all open the repository that you need and click the **Clone or Download** button.
> Then open console,move to the folder where you want to save your project and use this command (with your link)
 ```
   git clone https://github.com/SMRTPZ/HELPBOX.git 
 ```


### When you want to add your project
> First of all create a new project [here](https://github.com/SMTRPZ)
> Add file with the name ".gitignore" in your project root folder with such data(sample entries):
```
   .vs
   [Bb]in
   [Oo]bj
```
> Then enter commands in console:
 ```
   git init
   git add .
   git commit -m MessageInYourCommit
   git push LinkOfYourGithubProject (as in previous paragraph) 
 ```

### If you already have your project commited and want to make any changes, just enter
 ```
   git add .
   git commit -m MessageInYourCommit
   git push LinkOfYourGithubProject (as in previous paragraph) 
 ```
