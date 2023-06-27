# **test_repo**
## Here I will describe the meaning and differences between some of git commands

### **$ `git fetch` [remote repository]**
#### _Downloads the entire history from a remote repository into your local Git repo_

### **$ `git pull` [remote repository]**
#### _Downloads a history from a remote repository and merges it into the working directory_

### **Difference**
#### _The key difference between git fetch and pull is that git pull copies changes from a remote repository directly into your working directory, while git fetch does not. The git fetch command only copies changes into your local Git repo. The git pull command does both._

### **The `git commit --amend` command** 

### _This comand is a convenient way to change the last commit. It allows you to merge indexed changes with the previous commit without creating a new commit. It can be used to edit a comment on a previous commit without changing the state of the code in it. But such a change not only edits the last commit, but completely replaces it. That is, the modified commit will become a new entity with a separate reference. To Git, it will look like a new commit, which is marked with an asterisk (*)_.
