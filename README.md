# git-commands

## First exercises

1.git branch -m master main(stage changes, git add ., git commit -m "hdhd")
2.git remote add origin <remote_repo_url>
3.git remote -v
4.git push -u origin <branch>

### creating a new branch 
 1) git branch <branch-name>
 2) git checkout -b <branch-name>
 
### deleting branch 
  1) git branch -D <branch-name> this will delete a branch with its entire commits associate with it.
  2) git branch -d <branch-name> is used to delete a branch after it has fully merged.
  3) git push origin --delete <branch-name>(deleting a remote branch(git push origin --delete <branch_name>))

## Second exercises 
1. git stash save "messages"
2. git stash list
3. git stash pop bring the first stash in the queue, then git stash pop <stash_name>
4. you can use git stash apply <stash_name> to bring stash and keep it in stash list.


 
