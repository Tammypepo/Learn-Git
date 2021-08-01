Basic writing and formatting syntax [page](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

# Code for learning how to use git

Some basic Git commands are:

```
git status
git pull
git add
git commit
git push
git checkout
git merge
```

Setup your .gitconfig.

```
git config --global user.name "your name"
git config --global user.email youremail@example.com
```

Don't push these to git

- Username / Password / IP address
- Connfig file (Credentials)
- Private key
- Individual data like passport ID
- Secret!!

Use .gitignore instead [gitignore](https://github.com/github/gitignore)

```
filename.json
.cache
foldername/
.vscode/*
.idea/*
```

# Branching strategies
**Trunk-based development**
- Master/Main (Trunk)
- Feature
- Release

![github-large](https://trunkbaseddevelopment.com/trunk1c.png)

**Gitflow**
- Master/Main (only one)
- Feature
- Release
- Develop (only one)
- Hotfix

![github-large](https://i2.wp.com/lanziani.com/slides/gitflow/images/gitflow_1.png?zoom=2)
