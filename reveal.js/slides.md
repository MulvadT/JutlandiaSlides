# Git 101 

By  
Jutlandia  
Mads & Thomas  

--- 

### What is git?  
  - Version control system  
  - Share files between users        
        - History  
        - Conflicts  
        - Local changes  

-v- 

### When to use?  
  - Always use git  
    - Generally for project work  
      - By yourself  
      - With others  

-v- 


### How to get started?  
    - Install git  
    - Create a user on  
        - Github  
        - Gitlab  
        - Gitbucket  
    
    - Now you're good to go!  


---

## How to work in git  

-v-


### Creating a repo  

    - Git clone  
    - Git init  

-v-

### Git clone  

A repo is needed before using this method  
 - Done through cloud service  

Command:  
``` bash   
git clone https://depot.gitidyhoppity.com  
```  

-v-

#### Git init  

- Use this one time in your life  
    - Problems when pushing the first time  

Command:  
``` bash  
git init  
```  

-v-

### Adding files  

- used to stage files  
    - Preparation  
    - Don't add everything!  "."  

Command:  
``` bash  
git add files 
```  

-v-

### Viewing the staging  

- What info is given?  
    - Branch  
    - Up to date?  
    - What has been added  


-v-

### Committing  

- Adding a new version  
- Always accompanied by comment  
    - Short comment  
    - Well explaining comment   

Command:  
``` bash  
git commit -m "Very explaining message"  
```  
-v-

### Committing

Conventional Commits: https://www.conventionalcommits.org/en/v1.0.0/#summary  
    - Fix  
    - Feats  

-v-

### Pushing  
Used to share the code with the others  
    - Always pull before  

    
``` bash   
git push  

```

-v-

### Fetch  
Never used  
Don't think about it    
But gets updates from origin

``` bash  
git fetch  
```  

-v-

### Pulling  
To get what the others have uploaded to the repository   
    - Always pull  
    - Just pull  
    - Pulling is great  

``` bash  
git pull  
```  

--- 

## Branch (forgrening)  
Seperate track  

Used when implementing different features in the same code  

``` bash
git branch
git branch branchName
```
-v- 

### Pull requests
Reviews   
Conflicts  
Merge   



--- 
<!-- .slide: data-auto-animate -->

## Tools to help 

Use the terminal 

-v- 
<!-- .slide: data-auto-animate -->

## Tools to help 

Use the terminal   
Gitkraken   
Github desktop


--- 
<!-- .slide: data-auto-animate -->

## How to install

Windows:   
https://git-scm.com/downloads

Mac: 
1. Open terminal 
2. Type "git --version"

-v-
<!-- .slide: data-auto-animate -->

## How to install

Windows:   
https://git-scm.com/downloads

Mac: 
1. Open terminal 
2. Type "git --version"
   
Linux:
You know what to do.

--- 

## Tasks