// Add README.md file
$ git add README.md
 
$ git status
On branch master
Initial commit
 
Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
 
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Hello.class
        Hello.java
 
// You can use wildcard * in the filename
// Add all Java source files into Git repo
$ git add *.java
 
// You can also include multiple files in the "git add"
// E.g.,
// git add Hello.java README.md
 
$ git status
On branch master
Initial commit
 
Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Hello.java
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Hello.class
