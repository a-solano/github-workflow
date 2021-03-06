# GitHub Workflow

## Initialize the repo

```shell
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/<username>/<repository name>.git
git push -u origin master
git pull
```

## Clone Repo

```shell
git clone https://github.com/<username>/<repo name>.git
```

## New Branch

```shell
git checkout -b develop origin/master
git push -u origin develop
git pull
git checkout -b new-branch origin/develop
git add <newfile or . to all files>
git commit -m "second commit from new branch"
git push -u origin new-branch
git pull
```

## Pull request

```shell
git add README.md
git commit -m "Before pull request"
git push -u origin new-branch
git pull
```

## Checkout develop changes

```shell
git checkout develop
git pull
```

## Remove local branch

```shell
git branch -d <branch name>
```
