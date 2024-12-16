# Git Exercise 

## Bundle 1

### Exercise 1

```bash 

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop (master)
$ cd Alec/

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec (master)
$ clear

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec (master)
$ ls
 DSA-and-katas-8kyu-7kyu-Fundamentals/  'Git Fundamentals'/   JS-DOM/

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec (master)
$ mkdir Bundle1Exercise1

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec (master)
$ cd Bundle1Exercise1/

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec/Bundle1Exercise1 (master)
$ git init
Initialized empty Git repository in C:/Users/Prince BUGINGO/Desktop/Alec/Bundle1              Exercise1/.git/

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec/Bundle1Exercise1 (master)
$ ls
README.md

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec/Bundle1Exercise1 (master)
$ git add README.md

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec/Bundle1Exercise1 (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   README.md

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec/Bundle1Exercise1 (master)
$ git commit -m "New file"
[master (root-commit) 618b5c6] New file
 1 file changed, 3 insertions(+)
 create mode 100644 README.md

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec/Bundle1Exercise1 (master)
$ git branch -m master main

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec/Bundle1Exercise1 (main)

The above changed to main 

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec/Bundle1Exercise1 (main)
$ git branch -m main master

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec/Bundle1Exercise1 (master)

Changed back to master 

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec/Bundle1Exercise1 (master)
$ git branch -m master main  // change it back to main 

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec/Bundle1Exercise1 (main)
$ git remote add origin https://github.com/alecbideri/Gym-Git-Exercise-Solutions.git


PS C:\Users\Prince BUGINGO\Desktop\Alec\Bundle1Exercise1> git status 
On branch main
nothing to commit, working tree clean
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