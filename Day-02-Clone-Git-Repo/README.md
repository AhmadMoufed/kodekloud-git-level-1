## Day 02 – Clone Git Repository on Storage Server

### Question

The DevOps team established a new Git repository last week. The Nautilus application development team now requires a copy of this repository on the Storage Server.

**Details:**

* Repository location: `/opt/games.git`
* Clone destination: `/usr/src/kodekloudrepos`
* User: `natasha`
* No permission or directory changes allowed

### Solution

```bash
ssh natasha@ststor01
cd /usr/src/kodekloudrepos/
git clone /opt/games.git
```
