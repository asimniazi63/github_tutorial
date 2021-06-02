# Github Commands

- To configure your git:

```
git config --global user.name "asimniazi63"

git config --global user.email "asimniaz63@gmail.com"

```

- Create Project Name

```
mkdir New_Project
cd New_Project
```

- Initialize Git
```
git init
```

- Create/Add New Files:

```
touch Readme.md
```

- To check if the file is part of repo:
```
git status
```

- Staging:
Staged files are files that are ready to be committed to the repository you are working on. You will learn more about commit shortly.

```
git add Readme.md
```

The file should be Staged. Let's check the status::

```
git status
```

Add another or all files. (Using --all instead of individual filenames will stage all changes (new, modified, and deleted) files.)

- Git commit
```
git commit -m "Adding two sample files"
```

Skip staging and directly commit. Why?
Answer: Sometimes, when you make small changes, using the staging environment seems like a waste of time. It is possible to commit changes directly, skipping the staging environment. The -a option will automatically stage every changed, already tracked file.

check status in simple way by adding --short
```
git status --short
```

commit modified changes
```
git commit -a -m "Updated Readme.md"
```

- Push to Github
-- Branching

To add master branch:
```
git branch -M main
```

To create new branch:
```
git branch development
```

checkout is the command used to check out a branch. Moving us from the current branch, to the one specified at the end of the command:
```
git checkout hello-world-images
```

-- Branch Merging

add later on

- Push to github Branch

- add repo:
```
git remote add origin https://github.com/asimniazi63/github_tutorial.git
```

push code to main branch
```
git push -u origin main
```
