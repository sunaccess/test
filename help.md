
zzw@SKY-20190302CWV MINGW64 /d/GitTest (master)
$ git config --g
--get             --get-color       --get-regexp      --global
--get-all         --get-colorbool   --get-urlmatch

zzw@SKY-20190302CWV MINGW64 /d/GitTest (master)s
$ git config --global  user.name 'sunaccess'

zzw@SKY-20190302CWV MINGW64 /d/GitTest (master)
$ git config  --global user.email 'sunaccess@163.com'

zzw@SKY-20190302CWV MINGW64 /d/GitTest (master)
$ git c
checkout      cherry-pick   clean         commit
cherry        citool        clone         config

zzw@SKY-20190302CWV MINGW64 /d/GitTest (master)
$ git c
checkout      cherry-pick   clean         commit
cherry        citool        clone         config

zzw@SKY-20190302CWV MINGW64 /d/GitTest (master)
$ git cl
clean   clone

zzw@SKY-20190302CWV MINGW64 /d/GitTest (master)
$ git clone 'https://github.com/sunaccess/test.git'
Cloning into 'test'...
warning: You appear to have cloned an empty repository.

zzw@SKY-20190302CWV MINGW64 /d/GitTest (master)
$ cd test

zzw@SKY-20190302CWV MINGW64 /d/GitTest/test (master)
$ git a
add       am        apply     archive

zzw@SKY-20190302CWV MINGW64 /d/GitTest/test (master)
$ git
Display all 59 possibilities? (y or n)

zzw@SKY-20190302CWV MINGW64 /d/GitTest/test (master)
$ git a
add       am        apply     archive

zzw@SKY-20190302CWV MINGW64 /d/GitTest/test (master)
$ git add
Nothing specified, nothing added.
Maybe you wanted to say 'git add .'?

zzw@SKY-20190302CWV MINGW64 /d/GitTest/test (master)
$ git add test.js

zzw@SKY-20190302CWV MINGW64 /d/GitTest/test (master)
$ git c
checkout      cherry-pick   clean         commit
cherry        citool        clone         config

zzw@SKY-20190302CWV MINGW64 /d/GitTest/test (master)
$ git c
checkout      cherry-pick   clean         commit
cherry        citool        clone         config

zzw@SKY-20190302CWV MINGW64 /d/GitTest/test (master)
$ git c
checkout      cherry-pick   clean         commit
cherry        citool        clone         config

zzw@SKY-20190302CWV MINGW64 /d/GitTest/test (master)
$ git commit -m 'git test'
[master (root-commit) 6e9c79e] git test
 1 file changed, 1 insertion(+)
 create mode 100644 test.js

zzw@SKY-20190302CWV MINGW64 /d/GitTest/test (master)
$ git pu
pull   push

zzw@SKY-20190302CWV MINGW64 /d/GitTest/test (master)
$ git pu
pull   push

zzw@SKY-20190302CWV MINGW64 /d/GitTest/test (master)
$ git pu
pull   push

zzw@SKY-20190302CWV MINGW64 /d/GitTest/test (master)
$ git pull
Your configuration specifies to merge with the ref 'refs/heads/master'
from the remote, but no such ref was fetched.

zzw@SKY-20190302CWV MINGW64 /d/GitTest/test (master)
$ git push
fatal: unable to access 'https://github.com/sunaccess/test.git/': Could not resolve host: github.com

zzw@SKY-20190302CWV MINGW64 /d/GitTest/test (master)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 211 bytes | 52.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/sunaccess/test.git
 * [new branch]      master -> master

zzw@SKY-20190302CWV MINGW64 /d/GitTest/test (master)
$ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/sunaccess/test
   6e9c79e..12aa160  master     -> origin/master
Updating 6e9c79e..12aa160
Fast-forward
 test.js | 3 ++-
 1 file changed, 2 insertions(+), 1 deletion(-)

zzw@SKY-20190302CWV MINGW64 /d/GitTest/test (master)
$
