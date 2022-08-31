<h2 style = "color:red"> Hello, I am a git expert. want to learn git ? </h2>

## Basic git commands

1. git repo initialization

```sh
git init
```

2. To add all the files to stage

```sh
git add .
```

3. To commit the added files

```sh
git commit -m "your message"
```

4. To see the status

```sh
git status
```

5. To see git logs. That means your commit history and your head position and branch

```sh
git log
```

6. To see all git log

```sh
git log --all
```

7. To create a new branch

```sh
git branch branchname
```

8. To move your head to newly created branch

 ```sh
 git checkout branchname
 ```
 
9. To all the structure of your git with graph

```sh
git log --all --graph

```
 
 ## Now you want to upload all the things done here to a cloud server. Let's say push everthing to github
 
 1. create a repo in github
 
 
 > github.com


2. connect this repo with your local repo
 
 - you will get code there looks like below. copy and paste this in your terminal
 
 ```sh
git remote add origin https://github.com/md-thayyib/your_repo_name.git
```
3. 'master' is your branch name in local repo. But github using 'main' as main branch. So it is better make you branch name as 'main' insted of master


```sh
git branch -M main
```

4. Now you are ready to push your code to github repo


```sh
git push -u origin main
```


[referecne](https://dillinger.io/)
