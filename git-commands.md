# Git Related Commands
### Using less in command line. This is what "git log" uses
To navigate:
* f = for next page
* b = for previous page

To search:
* /query
* n = next match
* p = previous match

To quit:
* q = to quit

### Git Stash Use Cases
* stash changes
  * git stash
* list stash
  * git stash list
* show changes
  * git stash show stash@{0}
* apply the last stash
  * git stash apply
* apply specific stash 
  * git stash apply stash@{0}
* keep untracked files
  * git stash --include-untracked
* keep all even ignored ones
  * git stash --all
* name stashes for easy reference
  * git stash save "some easy reference here"
* start new branch from stash
  * git stash branch {branch name}
* grab single file from stash.
  If you have a same file in your working area and checking out the same file from stash then the stash changes will overwrite the local changes. 
  * git checkout stash-name -- file-name
* remove last stash and apply the changes. Except when there is a merge conflict then git won't remove the stash
  * git stash pop
* remove the last stash
  * git stash drop
* remove nth stash
  * git stash drop stash@{0}
* remove all stash
  * git stash clear
* selectively stash changes
  * git stash -p
