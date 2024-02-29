# Commands

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

- Git status: check in what conceptual area my file folder is 
  
  - verify uncommited changes
  
  - verify staged and unnstaged changes 
  
  - verify tasks 

- git log: all what you have saved in your local repository 
  
  - git log --help 
  
  - git log -n <number>
  
  - git log --abbrev-commit 
  
  - get out whit q = quit 

- git show <commit ID1> <commit ID2> OR git diff <commit ID1> <commit ID2> 
  
  - git diff showes more what you deleted 
  
  - in git show no direct comparison 
  
  - in git diff: direct comparison 

- git remote add <name><SSH> 
  
  - create a bridge between repositories
  
  - connect to a remote repository 
  
  - nothing is yet shared --> you built the bridge but not cross the bridge yet 
  
  - backupt created for only commited changes so not pdf and png  

- git push: cross the bridge to remote repository on Git Hub 
  
  - always fatal in 1st time, use following:
    
    git push --set-upstream folder_link master --> YES --> Password --> Done

- git reset <file> : unstage specific file 

- git rm <file> : remove file 
  
  
