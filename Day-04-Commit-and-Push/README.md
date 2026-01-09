## Day 04 – Add, Commit, and Push Files

### Task

Copy `index.html` into the Git repository, add it, commit it, and push it to the remote repository.

### Solution

```bash
ssh natasha@ststor01
sudo cp index.html /usr/src/kodekloudrepos/demo
cd /usr/src/kodekloudrepos/demo
git status
sudo git add .
sudo git commit -m "adding index.html file"
sudo git push origin master
```

### Result

* `index.html` added
* Commit created
* Changes pushed successfully to remote repository
