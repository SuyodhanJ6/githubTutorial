## This is the Git tutorial

### 1. Initialize repository
git init 

### 2. Creating global name 
git config --global user.name "Prashant Malge" 

### 3. Creating global email 
git config --global user.email "prashantmalge181@gmail.com"

### 4. Checking status
git status 

### 5. Adding File 
git add README.md 

### 6. Adding all Files 
git add . 

### 7. Committing the file and write a msg
git commit -m "This is my First Commit"

### 8. Checking Which Branch is using 
git branch

### 9. remote -v
git remote -v

### 10. Pushing file in the main branch
git push origin main

## Creating another branch 
git branch developer1

## Switching one branch to another branch
git checkout main/developer1

## Merging To Main Branch
git merge developer1

## I created Developer2 branch
git brach developer2

## Checking all logs 
git log

### Checking all log in details
git log -p

### Deleting branch
git branch -d developer1

