
jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (acido_b2)
$ cd acido_it120_activity1
bash: cd: acido_it120_activity1: No such file or directory

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1
$ git init
Initialized empty Git repository in C:/Users/jstin/acido_it120_activity1/.git/

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (main)
$ git remote add acido_it120_activity1 https://github.com/C1dd03/Acido_IT120_Activity1.git

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (main)
$ touch profile.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (main)
$ touch education.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (main)
$ touch background.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (main)
$ touch readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (main)
$ touch test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (main)
$ git add .

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (main)
$ notepad profile.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (main)
$ notepad education.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (main)
$ notepad background.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (main)
$ notepad test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (main)
$ git add .

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (main)
$ git commit -m "save all files"
[main (root-commit) aae7f15] save all files
 5 files changed, 14 insertions(+)
 create mode 100644 background.txt
 create mode 100644 education.txt
 create mode 100644 profile.txt
 create mode 100644 readme.txt
 create mode 100644 test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (main)
$ git push -u acido_it120_activity1 main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (7/7), 681 bytes | 681.00 KiB/s, done.
Total 7 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/C1dd03/Acido_IT120_Activity1.git
 * [new branch]      main -> main
branch 'main' set up to track 'acido_it120_activity1/main'.

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (main)
$ git branch acido_b1

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (main)
$ git branch acido_b2

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (main)
$ git branch acido_b3

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (main)
$ git branch acido_b4

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (main)
$ git switch acido_b1
Switched to branch 'acido_b1'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (acido_b1)
$ notepad profile.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (acido_b1)
$ notepad readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (acido_b1)
$ git add .

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (acido_b1)
$ git commit -m "Save profile & readme files"
[acido_b1 5342039] Save profile & readme files
 2 files changed, 106 insertions(+), 1 deletion(-)

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (acido_b1)
$ git push -u acido_it120_activity1 acido_b1
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 1.23 KiB | 1.23 MiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'acido_b1' on GitHub by visiting:
remote:      https://github.com/C1dd03/Acido_IT120_Activity1/pull/new/acido_b1
remote:
To https://github.com/C1dd03/Acido_IT120_Activity1.git
 * [new branch]      acido_b1 -> acido_b1
branch 'acido_b1' set up to track 'acido_it120_activity1/acido_b1'.

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (acido_b1)
$ git switch acido_b2
Switched to branch 'acido_b2'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (acido_b2)
$ notepad education.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (acido_b2)
$ notepad readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (acido_b2)
$

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (acido_b2)
$ git add .

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (acido_b2)
$ git commit -m "update education & readme files"
[acido_b2 cc7650f] update education & readme files
 2 files changed, 136 insertions(+)

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (acido_b2)
$ git push -u acido_it120_activity1 acido_b2
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 1.31 KiB | 1.31 MiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'acido_b2' on GitHub by visiting:
remote:      https://github.com/C1dd03/Acido_IT120_Activity1/pull/new/acido_b2
remote:
To https://github.com/C1dd03/Acido_IT120_Activity1.git
 * [new branch]      acido_b2 -> acido_b2
branch 'acido_b2' set up to track 'acido_it120_activity1/acido_b2'.

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (acido_b2)
$ git switch acido_b3
Switched to branch 'acido_b3'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (acido_b3)
$ git rm test.py
rm 'test.py'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (acido_b3)
$ notepad background.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (acido_b3)
$ notepad readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (acido_b3)
$ git add .

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (acido_b3)
$ git commit -m "Update background & readme files, Delete test file"

jstin@DESKTOP-0J7J0RJ MINGW64 ~/acido_it120_activity1 (acido_b3)
$ git push -u acido_it120_activity1 acido_b3




