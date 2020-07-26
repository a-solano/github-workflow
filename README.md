# GitHub Workflow

## Initialize the repo

```shell
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/<sername>/<repository name>.git
git push -u origin master
```

## New Branch

```shell
git checkout -b develop origin/master
git push -u origin develop
git checkout -b new-branch origin/develop
git add <newfile or . to all files>
git commit -m "second commit from new branch"
git push -u origin new-branch
```
