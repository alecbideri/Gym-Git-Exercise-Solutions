# Git Exercis 

## Bundle 1

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
$ git branch -m master main

Prince BUGINGO@DESKTOP-B1CA60T MINGW64 ~/Desktop/Alec/Bundle1Exercise1 (main)
.gitt remote add origin https://github.com/alecbideri/Gym-Git-Exercise-Solutions.
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=<push|fetch>]
                          set up remote as a mirror to push to or fetch from


```