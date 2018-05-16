# git-create

This script creates a git repo (public or private) using only shell script, no longer need to go to a web browser to create a new repo and then clone it.

### Useage:
```
$ git create my_new_repo (any character indicating you want a private repor)
```

### Installing

1) Clone this repository
```
$ git clone https://github.com/saccharide/git-create
```
2) Update the script with your own username
```
curl -u 'INSERT_USERNAME' https://api.github.com/user/repos -d "{\"name\":\"$repo_name\"}"
git remote add origin git@github.com:INSERT_USERNAME/$repo_name.git
```
3) Setup the script in your ~/bin (Make one if you don't currently have one), then perform the following
```
# Move script
$ mv git-create ~/bin
```

4) Add Permission to run
```
$ chomod +x git-create
```
(Make sure you have set up SSH key in your account setting for this to work well)

## Author

* **Saccharide**
