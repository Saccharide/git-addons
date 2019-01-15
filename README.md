# git-create

This script creates a git repo (public or private) using only shell script, no longer need to go to a web browser to create a new repo and then clone it.

### Installing

```
git clone https://github.com/saccharide/git-addons && chmod +x install.sh && ./install.sh 
```
(SSH key for easier commits)
```
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```
### Usage:
```
git create USERNAME REPO_NAME [private] (optional third field, empty for public repo)

git commit-all "COMMIT MESSAGE"

git pushom
```

## Author
* **Saccharide**
