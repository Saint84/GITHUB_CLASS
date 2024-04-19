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

### Logs: Commits Management:
In order to list all projects's commits you can use the follow command
 - > git log
 - > git log --oneline
 - > git log -n (n is a integer number)
 - > git log --oneline -n

### Commits:
 - > git commit -m (msg)
 - > git commit --amend -m (new msg) 
 (PS: "Ammend" command change only the currently commit modify msgs and files)

### Time travel with checkout:
 - > git log --oneline
 - > git checkout (commint id)
 - > git checkout Master

### Reverse and Reset:
In order to remove the last alterations on branch, you can use the follow command line
 - > git reverse (last commid id).
PS: Keep in mind you must use the last commit id.

### Differences:
In order to check the currently modifications, you can use:
 - > git diff --stage


### Merge:
In order to get the alterations in another branches you can use `merge` command
 - > git merge (branch name)

It's likely that you will encounter merge conflicts.

### Restore
 - > git restore --staged (file name)

### x. Useful Links 💥
- [Explanation: .gitignore](https://git-scm.com/docs/gitignore#:~:text=A%20gitignore%20file%20specifies%20intentionally,gitignore%20file%20specifies%20a%20pattern.)
- [Automation: gitignore Creation](https://www.toptal.com/developers/gitignore)


