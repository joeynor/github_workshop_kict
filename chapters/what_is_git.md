# What is Git

1. Speed
2. Simplicity
3. Fully Distributed
4. Excellent support for parallel development, support for hundreds of parallel branches.
5. Integrity

## History of Git
Linus Torvalds, creator of Linux Operating System

## How Git stores revisions
Git stores changes differently
### other VCS
Version control systems store the difference between the two versions. For example, consider File A that got changed three times. The First version of the file will be stored as is, in the sense complete file will be stored. As new versions are introduced only the difference from the previous version will be saved.
![other vcs](https://www.toolsqa.com/gallery/Git/1.How%20other%20CVS%20store%20changes.jpg)

### Git
Git, on the hand, stores the Snapshot of the changed file. For example, if you made a change to File A, a complete snapshot of the changed file is stored. If a file has not changed between two versions, Git will keep a reference of the original file instead of copying it again in the new version.

![gitvcs](https://www.toolsqa.com/gallery/Git/2.How%20other%20GIT%20store%20changes.jpg)

## Git is Distributed
Version Control Systems like CVS and SVN require you to be connected to the server for every operation. This gives Git a significant speed advantage. 

## Git Integrity
Internally Git creates a checksum value from the content of the file and then verifies it while transmitting or storing data.

# Why use Git
1. Performance
2. Security
3. Branching Model
  -  context switching
  -  role-based code
  -  disposable experimentation (try something out, if does not work, delete it without any loss of code).
4. Staging Area
5. Distributed
6. Open Source

# Git and Github
I have a secret, most of this material are taken online, so we will just refer to the [original](https://www.toolsqa.com/git/difference-between-git-and-github/) content from this point on. 
