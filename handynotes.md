
## Initiate git repository
```Bash
echo "# test" >> README.md
echo >> .gitignore
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

