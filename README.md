# belajarGIT
tugas git-github
Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas.css
4. Tugas.js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject

Daftar perintah GiT
...

perintah belajar git
Acer@Honami MINGW64 ~
$ cd "C:\github\tugas pw"

Acer@Honami MINGW64 /c/github/tugas pw
$ git clone "https://github.com/xaviermamangkey44/belajarGIT.git"
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

Acer@Honami MINGW64 /c/github/tugas pw
$ git config --global user.email "xaviermamangkey44@gmail.com"

Acer@Honami MINGW64 /c/github/tugas pw
$ cd belajarGiT

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-git)
$ touch Tugas-git.txt

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-git)
$ git add Tugas-git.txt

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-git)
$ git commit -m "commit 1 tambah tugasgit dan keterangan"
[Tugas-git a243442] commit 1 tambah tugasgit dan keterangan
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git merge Tugas-git
Updating 67ce90c..a243442
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 313 bytes | 313.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/xaviermamangkey44/belajarGIT.git
   67ce90c..a243442  main -> main

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-html)
$ touch Tugas-html.txt

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-html)
$ git add Tugas-html.txt

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-html)
$ git commit -m "commit 2 tugashtml"
[Tugas-html 18a990c] commit 2 tugashtml
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git merge Tugas-html
Updating a243442..18a990c
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git branch
  Tugas-git
  Tugas-html
* main

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 331 bytes | 331.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/xaviermamangkey44/belajarGIT.git
   a243442..18a990c  main -> main

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-css)
$  touch Tugas-css.txt

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-css)
$ git add Tugas-css.txt

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-css)
$ git commit -m "commit di css"
[Tugas-css 1f628d7] commit di css
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git merge Tugas-css
Updating 18a990c..1f628d7
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 366 bytes | 366.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/xaviermamangkey44/belajarGIT.git
   18a990c..1f628d7  main -> main

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-js)
$  touch Tugas-js.txt

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-js)
$ git add Tugas-js.txt

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-js)
$ git commit -m "commit di js"
[Tugas-js 113866e] commit di js
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git merge Tugas-js
Updating 1f628d7..113866e
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$  git push origin main
aEnumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 292 bytes | 292.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)

remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/xaviermamangkey44/belajarGIT.git
   1f628d7..113866e  main -> main

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-midProject)
$ touch Tugas-midProject

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-midProject)
$ git add Tugas-midProject

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-midProject)
$ git commit -m "commit di midproject"
[Tugas-midProject aea6e83] commit di midproject
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git merge Tugas-midProject
Updating 113866e..aea6e83
Fast-forward
 Tugas-midProject | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 290 bytes | 290.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/xaviermamangkey44/belajarGIT.git
   113866e..aea6e83  main -> main

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-php)
$ touch Tugas-php.txt

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-php)
$ git add Tugas-php.txt

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-php)
$ git commit -m "commit di php"
[Tugas-php b1cf65f] commit di php
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git merge Tugas-php
Updating aea6e83..b1cf65f
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 290 bytes | 290.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/xaviermamangkey44/belajarGIT.git
   aea6e83..b1cf65f  main -> main

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-finalProject)
$ touch Tugas-finalProject

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-finalProject)
$ git add Tugas-finalProject

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-finalProject)
$ git commit -m "commit di finalproject"
[Tugas-finalProject 252a54b] commit di finalproject
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git merge Tugas-finalProject
Updating b1cf65f..252a54b
Fast-forward
 Tugas-finalProject | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 301 bytes | 301.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/xaviermamangkey44/belajarGIT.git
   b1cf65f..252a54b  main -> main

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git push origin -all
error: did you mean `--all` (with two dashes)?

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git push origin --all
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/xaviermamangkey44/belajarGIT.git
 * [new branch]      Tugas-css -> Tugas-css
 * [new branch]      Tugas-finalProject -> Tugas-finalProject
 * [new branch]      Tugas-git -> Tugas-git
 * [new branch]      Tugas-html -> Tugas-html
 * [new branch]      Tugas-js -> Tugas-js
 * [new branch]      Tugas-midProject -> Tugas-midProject
 * [new branch]      Tugas-php -> Tugas-php

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git branch
  Tugas-css
  Tugas-finalProject
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
* main

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git commit -m "commit main"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git add .

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$ git commit main
error: pathspec 'main' did not match any file(s) known to git

Acer@Honami MINGW64 /c/github/tugas pw/belajarGiT (main)
$






perintah tik2032

Acer@Honami MINGW64 ~
$ cd "C:\github\tugas pw\TIK2032-Project"

Acer@Honami MINGW64 /c/github/tugas pw/TIK2032-Project
$ git clone "https://github.com/xaviermamangkey44/TIK2032-Project.git"
Cloning into 'TIK2032-Project'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

Acer@Honami MINGW64 /c/github/tugas pw/TIK2032-Project
$ git config --global user.email "xaviermamangkey44@gmail.com"

Acer@Honami MINGW64 /c/github/tugas pw/TIK2032-Project
$ cd TIK2032-Project

Acer@Honami MINGW64 /c/github/tugas pw/TIK2032-Project/TIK2032-Project (main)
$ git checkout -b testbranch1
Switched to a new branch 'testbranch1'

Acer@Honami MINGW64 /c/github/tugas pw/TIK2032-Project/TIK2032-Project (testbranch1)
$ touch testbranch1.txt

Acer@Honami MINGW64 /c/github/tugas pw/TIK2032-Project/TIK2032-Project (testbranch1)
$ git add testbranch1.txt

Acer@Honami MINGW64 /c/github/tugas pw/TIK2032-Project/TIK2032-Project (testbranch1)
$ git commit -m "commit testbranch"
[testbranch1 16f570d] commit testbranch
 1 file changed, 1 insertion(+)
 create mode 100644 testbranch1.txt

Acer@Honami MINGW64 /c/github/tugas pw/TIK2032-Project/TIK2032-Project (testbranch1)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Acer@Honami MINGW64 /c/github/tugas pw/TIK2032-Project/TIK2032-Project (main)
$ git merge testbranch
merge: testbranch - not something we can merge

Acer@Honami MINGW64 /c/github/tugas pw/TIK2032-Project/TIK2032-Project (main)
$ git merge testbranch1
Updating 462239b..16f570d
Fast-forward
 testbranch1.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 testbranch1.txt

Acer@Honami MINGW64 /c/github/tugas pw/TIK2032-Project/TIK2032-Project (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 296 bytes | 296.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/xaviermamangkey44/TIK2032-Project.git
   462239b..16f570d  main -> main

Acer@Honami MINGW64 /c/github/tugas pw/TIK2032-Project/TIK2032-Project (main)
$
