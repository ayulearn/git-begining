# Git Tutorial for Beginners 
---
**This document is about how to use git first time** 
---
__Facts Good to Know Before Start-__ 
+ All git command starts with `git`
+ Git and github both are different.
+ You don't need github account for using git.
+ You don't need internet for using git.
+ git is a local repository works on your system. 
+ github is cloud repository use to push your local work on cloud
+ github give ease for collabration
+ alternate of github is bigbucket, gitlab etc.
---

## Steps
+ check the `status` wether git is initisalise or not 
    ```git
     git status
    ```
    + if output is :
    ![git status output](https://github.com/ayulearn/git-practice/blob/main/Screenshot%202022-01-05%20105957.png)
      ```git
      $ git status
      fatal: not a git repository (or any of the parent directories): .git
      ```
    + then use `init`
     ```git
     git init
     ```
   
    ![git init output](https://github.com/ayulearn/git-practice/blob/main/Screenshot%202022-01-05%20111014.png)
    
    after this `git status` looks like :-
    
    ![git status](https://github.com/ayulearn/git-practice/blob/main/3.png)
    
+ configure `user.name` and `user.email`

    + to check `user.name`
     ```git 
     git config user.name
     ```
     + to check `user.email`
      
          ```git
           git config user.email
          ```
     + if the output is:-
    ![user name output](https://github.com/ayulearn/git-practice/blob/main/4.png)
    
     + configure `user.name` and `user.email`
     ```git
     git config --global user.name "Your Name"
     git config --global  user.email "yourActualEmailWhichYouGoingToUseForGithubAccount"
     ```
     then again check `user.name` and `user.email`
     
     ![output](https://github.com/ayulearn/git-practice/blob/main/5.png)
     
     * NOW YOU ARE READY TO COMMIT *
     
     [my first commit](git@github.com:ayulearn/my-first-commit.git)

 

