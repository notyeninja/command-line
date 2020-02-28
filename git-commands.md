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
