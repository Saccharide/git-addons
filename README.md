# git-addons

This script creates a git repo (public or private) using only shell script, no longer need to go to a web browser to create a new repo and then clone it.

### Installing

```
git clone https://github.com/saccharide/git-addons && chmod +x INSTALL && ./INSTALL
```
(SSH key for easier commits)
```
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```
### Usage:
```
git create USERNAME REPO_NAME [private] (optional third field, empty for public repo)

git comall "COMMIT MESSAGE"

git pushom

git pullom
```

## Author
**Saccharide**
