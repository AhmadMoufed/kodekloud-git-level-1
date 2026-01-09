# KodeKloud – Git Level 1 Solutions

This document contains step-by-step solutions for **KodeKloud Git Level 1** labs performed on the Storage Server in the Stratos DC.

---

## Day 01 – Set Up Git Repository on Storage Server

### Question
The Nautilus development team has provided requirements to the DevOps team for a new application development project, specifically requesting the establishment of a Git repository.

**Requirements:**
1. Utilize `yum` to install the git package on the Storage Server
2. Create a bare repository named `/opt/games.git` (exact name required)

### Solution
```bash
ssh natasha@ststor01
yum install git -y
git init --bare /opt/games.git
