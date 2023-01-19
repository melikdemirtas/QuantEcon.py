In the following you can find my first session on git bash console. I think it is done using VIM editor but it's not fun at all please use console in the next session.
melik@LAPTOP-H3QOQ4RH MINGW64 ~
$ pwd
/c/Users/melik

melik@LAPTOP-H3QOQ4RH MINGW64 ~
$ cd D: Administrator@MyWindows
bash: cd: too many arguments

melik@LAPTOP-H3QOQ4RH MINGW64 ~
$ cd D:

melik@LAPTOP-H3QOQ4RH MINGW64 /d
$ mkdir git

melik@LAPTOP-H3QOQ4RH MINGW64 /d
$ cd git

melik@LAPTOP-H3QOQ4RH MINGW64 /d/git
$ git config --global user.name "melikdemirtas"

melik@LAPTOP-H3QOQ4RH MINGW64 /d/git
$ git config --global user.email "melikdemirtas@gmail.com"

melik@LAPTOP-H3QOQ4RH MINGW64 /d/git
$ git clone https://github.com/QueantEcon/QueamtEcon.py
Cloning into 'QueamtEcon.py'...
remote: Repository not found.
fatal: repository 'https://github.com/QueantEcon/QueamtEcon.py/' not found

melik@LAPTOP-H3QOQ4RH MINGW64 /d/git
$ git clone https://github.com/QueantEcon/QueantEcon.py
Cloning into 'QueantEcon.py'...
remote: Repository not found.
fatal: repository 'https://github.com/QueantEcon/QueantEcon.py/' not found

melik@LAPTOP-H3QOQ4RH MINGW64 /d/git
$ git clone https://github.com/QuantEcon/QuantEcon.py
Cloning into 'QuantEcon.py'...
remote: Enumerating objects: 9386, done.
remote: Counting objects: 100% (1161/1161), done.
remote: Compressing objects: 100% (514/514), done.
remote: Total 9386 (delta 764), reused 926 (delta 625), pack-reused 8225
Receiving objects: 100% (9386/9386), 18.80 MiB | 2.24 MiB/s, done.
Resolving deltas: 100% (6262/6262), done.

melik@LAPTOP-H3QOQ4RH MINGW64 /d/git
$ cd QuantEcon/
bash: cd: QuantEcon/: No such file or directory

melik@LAPTOP-H3QOQ4RH MINGW64 /d/git
$ cd QuantEcon.py/

melik@LAPTOP-H3QOQ4RH MINGW64 /d/git/QuantEcon.py (main)
$ git add fibonacci.cpp
fatal: pathspec 'fibonacci.cpp' did not match any files

melik@LAPTOP-H3QOQ4RH MINGW64 /d/git/QuantEcon.py (main)
$ git add ReadmeNizam.txt

melik@LAPTOP-H3QOQ4RH MINGW64 /d/git/QuantEcon.py (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   ReadmeNizam.txt


melik@LAPTOP-H3QOQ4RH MINGW64 /d/git/QuantEcon.py (main)
$ git commit -m "Some Readme file to save these codes. I will visit them in the future" ReadmeNizam.txt
[main ec819b2] Some Readme file to save these codes. I will visit them in the future
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 ReadmeNizam.txt

melik@LAPTOP-H3QOQ4RH MINGW64 /d/git/QuantEcon.py (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

melik@LAPTOP-H3QOQ4RH MINGW64 /d/git/QuantEcon.py (main)
$ git push -u origin main7
error: src refspec main7 does not match any
error: failed to push some refs to 'https://github.com/QuantEcon/QuantEcon.py'

melik@LAPTOP-H3QOQ4RH MINGW64 /d/git/QuantEcon.py (main)
$ git push -u origin main
remote: Permission to QuantEcon/QuantEcon.py.git denied to melikdemirtas.
fatal: unable to access 'https://github.com/QuantEcon/QuantEcon.py/': The requested URL returned error: 403

melik@LAPTOP-H3QOQ4RH MINGW64 /d/git/QuantEcon.py (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

melik@LAPTOP-H3QOQ4RH MINGW64 /d/git/QuantEcon.py (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

melik@LAPTOP-H3QOQ4RH MINGW64 /d/git/QuantEcon.py (main)
$ ^[[200~cd git
bash: $'\E[200~cd': command not found

melik@LAPTOP-H3QOQ4RH MINGW64 /d/git/QuantEcon.py (main)
$ cd git
bash: cd: git: No such file or directory

melik@LAPTOP-H3QOQ4RH MINGW64 /d/git/QuantEcon.py (main)
$ cd D:/git

melik@LAPTOP-H3QOQ4RH MINGW64 /d/git
$ git clone https://github.com/melikdemirtas/QuantEcon.py
Cloning into 'QuantEcon.py'...
remote: Enumerating objects: 9215, done.
remote: Counting objects: 100% (1051/1051), done.
remote: Compressing objects: 100% (488/488), done.
remote: Total 9215 (delta 677), reused 823 (delta 541), pack-reused 8164
Receiving objects: 100% (9215/9215), 18.76 MiB | 3.51 MiB/s, done.
Resolving deltas: 100% (6157/6157), done.

melik@LAPTOP-H3QOQ4RH MINGW64 /d/git
$ cd QuantEcon.py/

melik@LAPTOP-H3QOQ4RH MINGW64 /d/git/QuantEcon.py (main)
$ git add ReadmeNizam.txt

melik@LAPTOP-H3QOQ4RH MINGW64 /d/git/QuantEcon.py (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   ReadmeNizam.txt


melik@LAPTOP-H3QOQ4RH MINGW64 /d/git/QuantEcon.py (main)
$ git commit -m "I added a readme file to store basic commands used in this session for  future reference." ReadmeNizam.txt
[main 8df327c] I added a readme file to store basic commands used in this session for  future reference.
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 ReadmeNizam.txt

melik@LAPTOP-H3QOQ4RH MINGW64 /d/git/QuantEcon.py (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

melik@LAPTOP-H3QOQ4RH MINGW64 /d/git/QuantEcon.py (main)
$ git push -u origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 329 bytes | 329.00 KiB/s, done.
Total 3 (delta 1), reused 1 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/melikdemirtas/QuantEcon.py
   67b9a41..8df327c  main -> main
branch 'main' set up to track 'origin/main'.

melik@LAPTOP-H3QOQ4RH MINGW64 /d/git/QuantEcon.py (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

melik@LAPTOP-H3QOQ4RH MINGW64 /d/git/QuantEcon.py (main)
$
