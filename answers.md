1. git version 2.34.0.windows.1
2. PS C:\Users\rober\git-lab> git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/etc/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.email=cp068622@ohio.edu
user.name=cpahls
PS C:\Users\rober\git-lab>
3. manule appeared
4. Initialized empty Git repository in C:/Users/rober/git-lab/.git/
PS C:\Users\rober\git-lab> git add .
PS C:\Users\rober\git-lab> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md

PS C:\Users\rober\git-lab>
5. PS C:\Users\rober\git-lab>
6. command became green
7. [master (root-commit) cf991a4] Initial commit
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
 create mode 100644 answers.md
PS C:\Users\rober\git-lab>
8. commit cf991a497ac365109ed1c95153c8ed244ac3d368 (HEAD -> master)
Author: cpahls <cp068622@ohio.edu>
Date:   Tue Jan 23 11:19:59 2024 -0500

    Initial commit
PS C:\Users\rober\git-lab>
9. info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 225 bytes | 225.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/cpahls/git-lab.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\rober\git-lab>
10. Nothing changed
11. Everything up-to-date
PS C:\Users\rober\git-lab>
12. The README.md has stuff in it now
13.  Directory: C:\Users\rober\git-lab2


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         1/23/2024  12:12 PM                git-lab_2


PS C:\Users\rober\git-lab2>
14. 
