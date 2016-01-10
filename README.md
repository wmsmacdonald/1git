# 1git
Git version control for individual files. 

Cleanly track configuration files (such as .vimrc) in separate repositories.

```
1git .vimrc commit -m "changes"
1git .vimrc push
```

Clone brings the file to your current directory:

```
1git clone git@github.com:my_user/my-repo.git
```

Retains the full merging and branching power of git:
```
1git .vimrc merge my_feature
```

Work with multiple 1git files in the same directory:
```
1git .vimrc commit -m "changes to file in one repo"
1git .bashrc commit -m "changes to file in another repo"
```
### Install
Copy the 1git file into /usr/bin and change the permissions:
```
sudo chmod 755 /usr/local/bin/1git
```
