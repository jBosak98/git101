# Git 101
#### Jakub Bosak
#### Akademickie Stowarzyszenie Informatyczne

---

# About Version Control

---

# What is Git?

* Snapshots, Not differences
* has integrity
* only adds data
* three states

---

## Three states

![Three states](images/three_states.png)

---

## setup your identity

```
git config --global user.name "Jakub Bosak"
git config --global user.email "jBosak98@gmail.com"
```

---

## your editor

```
git config --global core.editor vim
```

---

## You can check your settings

```
git config --list
```

---

## let's get started

```
git init
git add .
git commit -m "Initial commit"
```

---

## Cloning an existing repository

```
git clone git://git.kernel.org/pub/scm/git/git.git
```

---


## Recording Changes to the Repository

![lifecycle](images/lifecycle.png)

---


## Checking the Status of Your Files

```
git status
```

---
## tracking new files

```
git add .
```

---
## staging the files
###### the same command
```
git add .

```

---

## ignore files

.gitignore

---

## viewing changes

#### unstaged files: 
```
git diff
```

#### staged files: 
```
git diff --cached
```

## commiting the changes
```
git commit
```
---

## DEMO


