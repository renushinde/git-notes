Git is a version control system that helps us to track changes to a file over time.
## Basic git workflow
  1. First you create a directory.
  
  2. Cd into the directory.
  
  3. git init
  
  4. You make changes to file(s).
  
  5. git add . or git add filename
  
  6. git commit -m "added-these-changes"
  
## Backtracking(going back to history)

  1. Checkout the HEAD version to discard changes to the directory.IMP:If it's not commited yet. To do this use **git checkout HEAD file.extension** or **git checkout -- file.extension**
  2. **git diff file.extension** to check the difference between a file.
  3. Remove file from the staging area. **git reset HEAD file.extension**
  4. If the changes are commited then: Do a git log first, grab the SHA(second to the latest) and do **git reset SHA**
