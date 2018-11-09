
![](https://cdn-images-1.medium.com/max/2000/1*-MA6RMgLt-660MkVNkxhpg.jpeg)
## Initiate git repository
```Bash
echo "# test" >> README.md
echo "*.logs">> .gitignore
git init
git add *.*
git commit -m "first commit"
git remote add origin https://github.com/H3xHunter/<name_of_the_git>.git
git push -u origin master
git push -u origin development
```

##  Initiate a new feature
```Bash
# Start a new feature
git checkout -b new-feature development
...
<working here to something>
...
git commit -m "new feature"
git checkout development
git merge new-feature
git branch -d new-feature
```

## Connect to a remote repository
```bash
cd <folder>
git init
git remote add origin <remote_repo_url>
```

## Clone remote peository
```bash
git clone <remote_repo_url>
```

## Push a version
```bash
git add *.*
git commit -m "Message"
git push -f HEAD:<branch name>
```

## create git ignore

```Bash
cat "" > .gitignore
```
#### Ignore folders 
```Bash
folder_name/
```
#### Ignore a file
```
README.txt
```
#### Ignore files type
```Bash
*logs
```

