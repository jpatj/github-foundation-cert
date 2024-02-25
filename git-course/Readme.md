## Git Hidden Folder

There is a hidden folder called `.git` which tells you that our project is a git repo.

If we wanted to createa  git repo in a new project we create the folder and initialize that report using `git init`

```
mkdir /workspaces/temp/new-project
cd /workspaces/temp/new-project
git init
touch Readme.md
code Readme.md
git status

# make changes to readme.md
git commit -a -m "add readme file"
```

## Cloning

We can clone 3 ways: HTTPS, SSH, GitHub-CLI

Since we are using GitHub Codespaces we'll create a temp directory in our workspaces

```sh
mkdir /workspace/temp
cd /workspace/temp
```

### HTTPS

```sh
git clone https://github.com/bdrake-fs/github-foundation-cert.git
cd github-foundation-cert
```

## Commits

## Branches

## Stashing

## Merging