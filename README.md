# 1git
Git version control for individual files. 

Cleanly track configuration files (such as .vimrc) in separate repositories.

```
1git .vimrc commit -m "changes"
1git .vimrc push
```

Retains the full merging and branching power of git:
```
1git .vimrc merge my_feature
```

Work with multiple 1git files in the same directory:
```
1git .vimrc status
1git .bashrc commit -m "changes"
```
