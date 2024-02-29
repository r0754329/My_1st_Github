# Git and Github Dictionary

git: a versioning system that keeps track of changes - allows you to go back, allows for collaboration, is locally stored

Github: Where we can acces other's files, online repository for your codes (not only)

IMPORTANT: don't do double git init 

IMPORTANT

## Commands

- initialize timeline: git init 

- add a file: $ git add File A 

- git commit: final command --> git makes you write a message/ is this meaningfull enough
  
  - $ git commit -m "meaningful message"
  
  - meaningful message
    
    - Why was it changed
    
    - How this adresses the issue 
    
    - Effects due the change
    
    - Limitations of the change 
  
  - BE DISCRIPTIVE as possible --> better to have enough information than less 
  
  --> SAVES the updates version (snapshot/point in time) in the git repo

## Conceptual Areas

1. Developing Area: The working directory 

2. Staging Area: $git add. Dump what you want to commit. Using to prepare snapshot. Gives you some control

3. Local Repository: it is where your snapshots are saved. Locally in your computer --> ls  -la command --> .git --> git commit sent things to local repo

### Why command message

This message will later on help you or anyone else that has acces to it, to understand the context of changes and updates.

GIT status allows me to check what files are 

1. to be staged: you have committed this file or folder before, you have mmade new changes and git recognise the new changes are not yet add not commit

2. to be committed1; you have commited file before, you have made new changes and git recognises you have add but not commit

3. untracked files 

git add regex --> * : means everything 

# Routine

1. Git init

2. git add

3. git status 

4. git -m "meaningful message"
