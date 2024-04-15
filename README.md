# Introduction ✨


### 1. Creating a GITHUB Repo.
- Creating a new Repository and follow the next steps:
    - > git init
    - > git remote add origin https://github.com/Saint84/GITHUB_CLASS.git
    - > git push -u origin master or 
    - > git push -f origin master

### 2. My First Commit.
- Perform the follow commands to push the files to GITHUB Repository:
    - > git status
    - > git add .
    - > git commit -m "My FIrst Commit"
    - > git push

### 3. Creating a .gitignore File
A **gitignore** file specifies intentionally untracked files that Git should ignore. Files already tracked by Git are not affected. We are going to ignore an IGNORE.txt file.

### 4. Creating a new Branch.
Now we are going to create a new branch and create a simple python file on the APP directory. To creating a new branch just typing
 - > git branch (New Branch Name)
 - > git push --set-upstream origin Dev

You can list all branch in this repository using:
 - > git branch

### 5. Checkout.
To begin working on this new branch, you can use the `git checkout` command.

### 6. Deleting useless branches.
In order to remove any unnecessary branches, you can make use of the `-d` flag.

 - > git branch -d (branch name)

### Time travel with checkout:
 - > git log --oneline
 - > git checkout (commint id)



### x. Useful Links 💥
- [Explanation: .gitignore](https://git-scm.com/docs/gitignore#:~:text=A%20gitignore%20file%20specifies%20intentionally,gitignore%20file%20specifies%20a%20pattern.)
- [Automation: gitignore Creation](https://www.toptal.com/developers/gitignore)


