# Git Exercise 

## Bundle 1 Exercise 1

###  Creating a folder , file and git initiation 

```bash 

## directory navigation 

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop (master)
$ cd Alec/

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec (master)
$ clear

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec (master)
$ ls
 DSA-and-katas-8kyu-7kyu-Fundamentals/  'Git Fundamentals'/   JS-DOM/


## creation of new project folder 

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec (master)
$ mkdir Bundle1Exercise1

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec (master)
$ cd Bundle1Exercise1/


## git initialization 

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec/Bundle1Exercise1 (master)
$ git init
Initialized empty Git repository in C:/Users/Prince BUGINGO/Desktop/Alec/Bundle1              Exercise1/.git/

## check the file creation in the folder 

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec/Bundle1Exercise1 (master)
$ ls
README.md

## stagin the file on the default master branch 

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec/Bundle1Exercise1 (master)
$ git add README.md

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec/Bundle1Exercise1 (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   README.md

## First commit to the local repository 

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec/Bundle1Exercise1 (master)
$ git commit -m "New file"
[master (root-commit) 618b5c6] New file
 1 file changed, 3 insertions(+)
 create mode 100644 README.md

```

## Changing from master to main , vice versa 

```bash

## change from master to main 

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec/Bundle1Exercise1 (master)
$ git branch -m master main

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec/Bundle1Exercise1 (main)

## change it back to master 

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec/Bundle1Exercise1 (main)
$ git branch -m main master

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec/Bundle1Exercise1 (master)

## change it back to main 

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec/Bundle1Exercise1 (master)
$ git branch -m master main  

```

## Add remote connection and push changes to the online repository

``` bash

## Add remote connection 

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec/Bundle1Exercise1 (main)
$ git remote add origin https://github.com/alecbideri/Gym-Git-Exercise-Solutions.git


PS C:\Users\Prince BUGINGO\Desktop\Alec\Bundle1Exercise1> git status 
On branch main
nothing to commit, working tree clean

## Push to the origin main 

PS C:\Users\Prince BUGINGO\Desktop\Alec\Bundle1Exercise1> git push origin main 
fatal: HttpRequestException encountered.       
   An error occurred while sending the request.
Counting objects: 9, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (5/5), done.
Writing objects: 100% (9/9), 1.45 KiB | 106.00 KiB/s, done.
Total 9 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/alecbideri/Gym-Git-Exercise-Solutions.git
 * [new branch]      main -> main


```

## Creating new branches

```bash 

## branch status 

PS C:\Users\Prince BUGINGO\Desktop\Alec\Bundle1Exercise1> git branch 
* main
PS C:\Users\Prince BUGINGO\Desktop\Alec\Bundle1Exercise1> 

## creating the dev branch 

PS C:\Users\Prince BUGINGO\Desktop\Alec\Bundle1Exercise1> git branch dev
PS C:\Users\Prince BUGINGO\Desktop\Alec\Bundle1Exercise1> git branch
  dev
* main
PS C:\Users\Prince BUGINGO\Desktop\Alec\Bundle1Exercise1> 

## checkout to the dev branch , create test branch and switch to it .

PS C:\Users\Prince BUGINGO\Desktop\Alec\Bundle1Exercise1> git checkout dev
Switched to branch 'dev'
M       README.md       
PS C:\Users\Prince BUGINGO\Desktop\Alec\Bundle1Exercise1> git branch test
PS C:\Users\Prince BUGINGO\Desktop\Alec\Bundle1Exercise1> git checkout test 
Switched to branch 'test'
M       README.md
PS C:\Users\Prince BUGINGO\Desktop\Alec\Bundle1Exercise1> 

## checkout dev and delete test 

PS C:\Users\Prince BUGINGO\Desktop\Alec\Bundle1Exercise1> git checkout dev 
Switched to branch 'dev'
M       README.md       
PS C:\Users\Prince BUGINGO\Desktop\Alec\Bundle1Exercise1> git branch -d test 
Deleted branch test (was d27b73f).
PS C:\Users\Prince BUGINGO\Desktop\Alec\Bundle1Exercise1>

PS C:\Users\Prince BUGINGO\Desktop\Alec\Bundle1Exercise1> git branch 
  *dev
   main
PS C:\Users\Prince BUGINGO\Desktop\Alec\Bundle1Exercise1> 

## swtich back to main 

PS C:\Users\Prince BUGINGO\Desktop\Alec\Bundle1Exercise1> git checkout main 
Switched to branch 'main'
M       README.md        
PS C:\Users\Prince BUGINGO\Desktop\Alec\Bundle1Exercise1> 

```

## Above are all the commands used on the exercises .
