# This is a header (use #)
## This is a sub-header (use ##)
1. Item1 (use  1. )
2. Item2
3. Item3

<p> This is a paragraph </p>

<p> You can use html codes with github </p>

<p>To add an image, drag and drop image in explorer and then 
drag and drop image to code section</p>

You can use ```language to define language and then write code 
Like this: 
```py
import numpy as np
print("do nothing")
```
<br>
<p>To display the state of the code:-
    type git status in terminal</p>

<p>To clone a repos:-
    git clone <-some link-></p>

## Saving the file
### Terms:
1. Untracked: new files that git doesn't track
2. modified: changed
3. staged: file is ready to be committed
4. unmodified: unchanged

### To Save:
1. add: adds new changed files in your working directory to the Git staging area
    git add <-file name->
    ex: git add learn.md
2. commit: it is the record of change
    git commit -m "some message"
3. push: upload local repo content to remote repo 
    git push origin main

## Init command
    init: used to creat a new git repo
1. git init: let's say you created a dir without git repo then to create
            a git repo in that dir, use this command
2. git remote add origin <-link->: 
    
