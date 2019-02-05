# **So you installed git...**


## **1. Who are you?**

`git config --global user.name "John Doe`

`git config --global user.email johndoe@example.com`

### And what does git know about me?

`git config --list`

## **2. Create a repo!**

`git init`

### maybe you want to copy one?

`git clone http://projecturl`

# **What do you know about trees?**

* Working directory
* Index -> changes proposed for next revision
* Head -> usually points where the branch points

## **3. Introducing a change to index tree**

`git add <file>` adds file to staging index.

## **4. Wait, what have I modified?**

`git status`

## **5. Ok, ready to commit**

`git commit -m "My first commit message"`
Head and active branch point to new commit.
 