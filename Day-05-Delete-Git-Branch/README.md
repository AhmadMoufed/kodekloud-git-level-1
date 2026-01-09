## Day 05 – Delete Git Branch

### Question

Delete the branch named `xfusioncorp_demo` from the Git repository located at:

```
/usr/src/kodekloudrepos/demo
```

### Solution

```bash
ssh natasha@ststor01
cd /usr/src/kodekloudrepos/demo
sudo git branch
sudo git checkout master
sudo git branch -d xfusioncorp_demo
```

### Result

* Branch `xfusioncorp_demo` deleted successfully
