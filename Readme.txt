
aaron@Acera_PC MINGW64 ~
$ cd Desktop
bash: cd: Desktop: No such file or directory

aaron@Acera_PC MINGW64 ~
$ mkdir Acera_IT120_Act01

aaron@Acera_PC MINGW64 ~
$ cd Acera_IT120_Act01

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01
$ touch Profile.txt Education.txt Background.txt Readme.txt Test.py

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01
$ git init
git add .
git commit -m "Initial commit with Profile.txt, Education.txt, Background.txt, Readme.txt, and Test.py"
Initialized empty Git repository in C:/Users/aaron/Acera_IT120_Act01/.git/
[master (root-commit) b80ad28] Initial commit with Profile.txt, Education.txt, Background.txt, Readme.txt, and Test.py
 5 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Background.txt
 create mode 100644 Education.txt
 create mode 100644 Profile.txt
 create mode 100644 Readme.txt
 create mode 100644 Test.py

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ notepad Profile.txt

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ notepad Education.txt

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ notepad Background.txt

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ notepad Test,py

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ git init
git add .
git commit -m "Initial commit with Profile.txt, Education.txt, Background.txt, Readme.txt, and Test.py"
Reinitialized existing Git repository in C:/Users/aaron/Acera_IT120_Act01/.git/
[master dfd6bd8] Initial commit with Profile.txt, Education.txt, Background.txt, Readme.txt, and Test.py
 4 files changed, 14 insertions(+)
 create mode 100644 Test,py.txt

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ git checkout -b Acera_B1
Switched to a new branch 'Acera_B1'

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (Acera_B1)
$ notepad Profile.txt

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (Acera_B1)
$ git add Profile.txt

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (Acera_B1)
$ git commit -m "Updated Profile.txt in Acera_B1 branch"
[Acera_B1 5e54c68] Updated Profile.txt in Acera_B1 branch
 1 file changed, 7 insertions(+), 1 deletion(-)

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (Acera_B1)
$ git checkout -b Acera_B2
Switched to a new branch 'Acera_B2'

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (Acera_B2)
$ notepad Education.txt

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (Acera_B2)
$ git add Education.txt

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (Acera_B2)
$ git commit -m "Updated Education.txt in Acera_B2 branch"
[Acera_B2 d9e75bc] Updated Education.txt in Acera_B2 branch
 1 file changed, 3 insertions(+)

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (Acera_B2)
$ git checkout -b Acera_B3
Switched to a new branch 'Acera_B3'

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (Acera_B3)
$ notepad Background.txt

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (Acera_B3)
$ git add Background.txt

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (Acera_B3)
$ git commit -m "Updated Background.txt in Acera_B3 branch"
[Acera_B3 9e5393d] Updated Background.txt in Acera_B3 branch
 1 file changed, 2 insertions(+)

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (Acera_B3)
$ git rm Test.py
rm 'Test.py'

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (Acera_B3)
$ git commit -m "Removed Test.py in Acera_B3 branch"
[Acera_B3 4032ae7] Removed Test.py in Acera_B3 branch
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 Test.py

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (Acera_B3)
$ git checkout -b Acera_B4
Switched to a new branch 'Acera_B4'

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (Acera_B4)
$ git rm Test.py
fatal: pathspec 'Test.py' did not match any files

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (Acera_B4)
$ git commit -m "Removed Test.py in Acera_B4 branch"
On branch Acera_B4
nothing to commit, working tree clean

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (Acera_B4)
$ git checkout master
Switched to branch 'master'

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ notepad Readme.txt

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ git add Readme.txt

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ git commit -m "Added all Git commands in Readme.txt"
On branch master
nothing to commit, working tree clean

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ git remote add origin https://github.com/joedelacera12-ops/Acera_IT120_Act1.git

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ git push -u origin master
remote: Repository not found.
fatal: repository 'https://github.com/joedelacera12-ops/Acera_IT120_Act1.git/' not found

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ git remote add origin https://github.com/joedelacera12-ops/IT120.git
error: remote origin already exists.

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ git push -u origin master
remote: Repository not found.
fatal: repository 'https://github.com/joedelacera12-ops/Acera_IT120_Act1.git/' not found

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ git remote remove origin

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ git remote add origin https://github.com/joedelacera12-ops/IT120.git

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ git push -u origin master
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 12 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (9/9), 894 bytes | 894.00 KiB/s, done.
Total 9 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), done.
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/joedelacera12-ops/IT120/pull/new/master
remote:
To https://github.com/joedelacera12-ops/IT120.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ git push -u origin Acera_B1
git push -u origin Acera_B2
git push -u origin Acera_B3
git push -u origin Acera_B4
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 488 bytes | 488.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Acera_B1' on GitHub by visiting:
remote:      https://github.com/joedelacera12-ops/IT120/pull/new/Acera_B1
remote:
To https://github.com/joedelacera12-ops/IT120.git
 * [new branch]      Acera_B1 -> Acera_B1
branch 'Acera_B1' set up to track 'origin/Acera_B1'.
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 468 bytes | 468.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Acera_B2' on GitHub by visiting:
remote:      https://github.com/joedelacera12-ops/IT120/pull/new/Acera_B2
remote:
To https://github.com/joedelacera12-ops/IT120.git
 * [new branch]      Acera_B2 -> Acera_B2
branch 'Acera_B2' set up to track 'origin/Acera_B2'.
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 582 bytes | 582.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
remote:
remote: Create a pull request for 'Acera_B3' on GitHub by visiting:
remote:      https://github.com/joedelacera12-ops/IT120/pull/new/Acera_B3
remote:
To https://github.com/joedelacera12-ops/IT120.git
 * [new branch]      Acera_B3 -> Acera_B3
branch 'Acera_B3' set up to track 'origin/Acera_B3'.
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'Acera_B4' on GitHub by visiting:
remote:      https://github.com/joedelacera12-ops/IT120/pull/new/Acera_B4
remote:
To https://github.com/joedelacera12-ops/IT120.git
 * [new branch]      Acera_B4 -> Acera_B4
branch 'Acera_B4' set up to track 'origin/Acera_B4'.

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ git remove origin
git: 'remove' is not a git command. See 'git --help'.

The most similar command is
        remote

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$  git remote remove origin

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ ^C

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ git remote add origin https://github.com/joedelacera12-ops/IT120_Activities.git

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ git push -u origin master
remote: Repository not found.
fatal: repository 'https://github.com/joedelacera12-ops/IT120_Activities.git/' not found

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ git remote -v
origin  https://github.com/joedelacera12-ops/IT120_Activities.git (fetch)
origin  https://github.com/joedelacera12-ops/IT120_Activities.git (push)

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ git remote set-url origin https://github.com/joedelacera12-ops/IT120_Activities.git

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ git remote remove origin
git remote add origin https://github.com/joedelacera12-ops/IT120_Activities.git

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ git push -u origin master
remote: Repository not found.
fatal: repository 'https://github.com/joedelacera12-ops/IT120_Activities.git/' not found

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ git remote remove origin

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ git remote add origin https://github.com/joedelacera12-ops/joedelacera12-ops-IT120_Activities.git

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ git push -u origin master
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 12 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (9/9), 894 bytes | 894.00 KiB/s, done.
Total 9 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/joedelacera12-ops/joedelacera12-ops-IT120_Activities.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$ git push -u origin Acera_B1
git push -u origin Acera_B2
git push -u origin Acera_B3
git push -u origin Acera_B4
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 488 bytes | 488.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Acera_B1' on GitHub by visiting:
remote:      https://github.com/joedelacera12-ops/joedelacera12-ops-IT120_Activities/pull/new/Acera_B1
remote:
To https://github.com/joedelacera12-ops/joedelacera12-ops-IT120_Activities.git
 * [new branch]      Acera_B1 -> Acera_B1
branch 'Acera_B1' set up to track 'origin/Acera_B1'.
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 468 bytes | 468.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Acera_B2' on GitHub by visiting:
remote:      https://github.com/joedelacera12-ops/joedelacera12-ops-IT120_Activities/pull/new/Acera_B2
remote:
To https://github.com/joedelacera12-ops/joedelacera12-ops-IT120_Activities.git
 * [new branch]      Acera_B2 -> Acera_B2
branch 'Acera_B2' set up to track 'origin/Acera_B2'.
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 582 bytes | 582.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
remote:
remote: Create a pull request for 'Acera_B3' on GitHub by visiting:
remote:      https://github.com/joedelacera12-ops/joedelacera12-ops-IT120_Activities/pull/new/Acera_B3
remote:
To https://github.com/joedelacera12-ops/joedelacera12-ops-IT120_Activities.git
 * [new branch]      Acera_B3 -> Acera_B3
branch 'Acera_B3' set up to track 'origin/Acera_B3'.
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'Acera_B4' on GitHub by visiting:
remote:      https://github.com/joedelacera12-ops/joedelacera12-ops-IT120_Activities/pull/new/Acera_B4
remote:
To https://github.com/joedelacera12-ops/joedelacera12-ops-IT120_Activities.git
 * [new branch]      Acera_B4 -> Acera_B4
branch 'Acera_B4' set up to track 'origin/Acera_B4'.

aaron@Acera_PC MINGW64 ~/Acera_IT120_Act01 (master)
$
