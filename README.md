HP@Ephans MINGW64 ~
$ cd plpbasic
bash: cd: plpbasic: No such file or directory

HP@Ephans MINGW64 ~
$ cd C:\plpbasic

HP@Ephans MINGW64 /c/plpbasic
$ git init
Initialized empty Git repository in C:/plpbasic/.git/

HP@Ephans MINGW64 /c/plpbasic (master)
$ git remote add origin https://github.com/kiplangat69/ephantusplpbasic

HP@Ephans MINGW64 /c/plpbasic (master)
$ touch ephans.text

HP@Ephans MINGW64 /c/plpbasic (master)
$ nano ephans.text

HP@Ephans MINGW64 /c/plpbasic (master)
$ git add ephans.text
warning: in the working copy of 'ephans.text', LF will be replaced by CRLF the next time Git touches it

HP@Ephans MINGW64 /c/plpbasic (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   ephans.text


HP@Ephans MINGW64 /c/plpbasic (master)
$ git commit "Add ephans.text with message 'I kiplangat Ephantus is enjoying the journey. Thanks to plp for awarding me this opportunity can not take it for granted.Much appreciation to our instructors too atleast I can deferentiate much of the basics.
My best novel is 'Atomic Habits' by James clear.
how he defines the term "system" is awesome'"
error: pathspec 'Add ephans.text with message 'I kiplangat Ephantus is enjoying the journey. Thanks to plp for awarding me this opportunity can not take it for granted.Much appreciation to our instructors too atleast I can deferentiate much of the basics.
My best novel is 'Atomic Habits' by James clear.
how he defines the term system is awesome'' did not match any file(s) known to git

HP@Ephans MINGW64 /c/plpbasic (master)
$ git add ephans.txt
fatal: pathspec 'ephans.txt' did not match any files

HP@Ephans MINGW64 /c/plpbasic (master)
$ ls
ephans.text

HP@Ephans MINGW64 /c/plpbasic (master)
$ nano ephans.text

HP@Ephans MINGW64 /c/plpbasic (master)
$ ls
ephans.text

HP@Ephans MINGW64 /c/plpbasic (master)
$ git add ephans.text
warning: in the working copy of 'ephans.text', LF will be replaced by CRLF the next time Git touches it

HP@Ephans MINGW64 /c/plpbasic (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   ephans.text


HP@Ephans MINGW64 /c/plpbasic (master)
$ git commit -m "Add ephans.text file"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'HP@Ephans.(none)')

HP@Ephans MINGW64 /c/plpbasic (master)
$ git config user.name kiplangat69

HP@Ephans MINGW64 /c/plpbasic (master)
$ git config user.mail ephantuskiplangat69@gmail.com

HP@Ephans MINGW64 /c/plpbasic (master)
$ git commit -m "Add ephans.text file"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'HP@Ephans.(none)')

HP@Ephans MINGW64 /c/plpbasic (master)
$ git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

HP@Ephans MINGW64 /c/plpbasic (master)
$ git commit -m "Add ephans.text file"
[master (root-commit) b65f6ff] Add ephans.text file
 1 file changed, 3 insertions(+)
 create mode 100644 ephans.text

HP@Ephans MINGW64 /c/plpbasic (master)
$ git push origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 443 bytes | 443.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/kiplangat69/ephantusplpbasic/pull/new/master
remote:
To https://github.com/kiplangat69/ephantusplpbasic
 * [new branch]      master -> master

HP@Ephans MINGW64 /c/plpbasic (master)
$
# ephantusplpbasic
