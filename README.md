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

# Exercise 2 - Bundle 1

## Creating dev branch and checkout to it 

```bash 

## creating the branch and checking out on it 

gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % git branch 
* main
gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % git branch dev 
gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % git checkout dev
Switched to branch 'dev'
gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % git branch
* dev
  main
```

## Creating all requested html files 

```bash

gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % touch home.html
gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % touch about.html
gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % touch team.html

```

## Adding content on the html files 

```bash 

gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % touch team.html
gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % echo "<h1>Home page</h1>" > home.html 
gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % echo "<h1>About us</h1>" > about.html
gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % echo "<h1>our team</h1>" > team.html 

```
## Staging and stashing the files 

```bash 

gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % git status
On branch dev
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        about.html
        home.html
        team.html

nothing added to commit but untracked files present (use "git add" to track)
gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % git add .
gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % git stash push -m "Added content on the files"
Saved working directory and index state On dev: Added content on the files
gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % 

```

## pop and restore them all

```bash

On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html
        new file:   team.html

Dropped refs/stash@{0} (60f308fc0598cafb4967715efd9c3d549286179d)
gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % 

```

## stashing the team.html file 

```bash

gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % git restore --staged about.html home.html 
gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % git status
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        about.html
        home.html

gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % git stash push -m "stash team.html"
Saved working directory and index state On dev: stash team.html
gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % git status
On branch dev
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        about.html
        home.html

nothing added to commit but untracked files present (use "git add" to track)
gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % 

```

## Commit current changes and push them 

```bash 

gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % git add .
gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % git status
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html

gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % git commit -m "New files with content and README.md update"
[dev 13b9474] New files with content and README.md update
 Committer: Gym Ikirenga <gymikirenga@Ikirengas-iMac.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 2 files changed, 2 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html
gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % git push origin dev
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 387 bytes | 387.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/alecbideri/Gym-Git-Exercise-Solutions/pull/new/dev
remote: 
To https://github.com/alecbideri/Gym-Git-Exercise-Solutions.git
 * [new branch]      dev -> dev
gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % 

```

## Restore and reset the team.html file 

```bash
gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % git stash pop 
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html
```

## Rest team.html 

```bash
gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % git reset --hard 
HEAD is now at 13b9474 New files with content and README.md update
gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % git status 
On branch dev
nothing to commit, working tree clean
gymikirenga@Ikirengas-iMac Gym-Git-Exercise-Solutions % 

```



