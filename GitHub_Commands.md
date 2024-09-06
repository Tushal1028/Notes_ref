**first Install Git from git website**
</br>

**Than Install Some extations for vs code**
</br>
1.Git Blame
2.git-autoconfig
3.GitHub Theme      //Optinal


# Run This Command After Download Git

```
git config --global user.name "name"                    // To Set User Name
git config --global user.email "Your_Email@gmail.com"   // To Set Email 

git config --global core.editor "code --wait"
git config --global core.autocrlf "input"

```

# Log Commands
```
git status -s  //To see status
git log
git log --oneline
git log --graph
```
 
# Branch Commands
```
git branch branch_name          //To create Branch
git switch branch_name          //To Switch Branch
git branch -d branch_name       // To Delete Branch
git switch -c branch_name       //To create branch and switch as well

```

# Go Back To previous Commit
```
git reset --hard HEAD~1         //for one stpe
git reset --hard HEAD~2         //for two stpe and so on
```

# GitHub Commands 
## create a new repository on the command line
```
echo "# Notes_ref" >> README.md         //Optional
git init
git add .
git commit -m "first commit"
git branch -M main(Branch name)
git remote add origin URL(https://github.com/Tushal1028/Notes_ref.git)
git push -u origin main(Branch Name)
```
##  push an existing repository from the command line
```
git remote add origin URL(https://github.com/Tushal1028/Notes_ref.git)
git branch -M main(Branch name)
git push -u origin main
```
