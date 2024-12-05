# Questions
## 1.	List three major version control software for software engineering.
Git, Bitbucket, CVS
## 2.	What are the main advantages to using Git in your software development, and how is it useful for game developers.
Allows for easy management and organisation of software development with tracked changes and version history, where developers all contribute to the same repository. Allows for multiple users to work on different parts of a project at the same time. Has functionality for merging two versions of a file or project.
## 3.	Define the following terms in relation to Git. Branch, Pull, Push, repository, working copy, merge
### Branch
A separate version of the main repository that exists alongside main and other branches, for a separate timeline of version control.
### Pull
Fetches the changes from the remote repository and updates the local repository with those changes
### Push
Uploads the local repository changes to the remote repository as commits
### repository
The place where projects/files are stored and their version history tracked
### working copy
The local git repository
### merge
Allows branches containing different changes to be combined into a single branch
## 4.	If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git.
- Security policies relating to what data must remain private and how it is stored.
- Version Control policy relating to git procedures for how git should be used e.g. how branches and merges should be used
- Documentation procedures
- Backup procedures
## 5.	Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts.
- Meld
- Beyond Compare 3
- Perforce Merge
- Kaleidoscope (Mac)
- VS Code
## 6.	In a merged source code file, how does Git let you know there is a conflict?
When a user attempts to merge, git will tell you about any merge conflicts. 
## 7.	What are the steps you can take to resolve Git conflicts?
You can use "git mergetool" to address each conflict individually.
After you address every conflict the merge can proceed.
## 8.	What does git revert do, and how can you use it?
It undoes a previous commit's changes while keeping other changes intact. It's used to revert specific changes without needing to roll back to a previous commit entirely or create a fork from an earlier commit.
## 9.	What does git reset do, and how can you use it? 
Reverts to the state of an earlier commit, as it existed when the commit was committed. It undoes changes to the repository.
## 10.	What is the difference between git revert and git reset?
revert undoes the changes of a specific commit without affecting other commits, while reset disregards all changes after a specific commit, essentially rolling back to a previous state in time.
## 11.	True or False: It is okay to commit broken code to the main branch.
False
## 12.	True or False: You should commit related changes. For example, fixing two different bugs should produce two separate commits.
True
## 13.	Describe what is DevOps, how is it useful for game developers?
It's a methodology consisting of tools, practices and philosphies for automating and integrating processes between software development and IT operations, hence the name DevOps
## 14.	List what tools can be used with DevOps. Give a brief description of each one. (at least 3)
- Git
- Amazon Web Services
- Microsoft Azure
- Raygun
- JMeter
## 15.	What is CI/CD and how can it be used to automate the game development process?
It stands for Continuous Integration an Continuous Delivery. It can automate the game development process with automated testing, automated user management, code quality tracking, automated security features, automated cloud integrations