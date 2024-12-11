### Imagine you are working at a game studio, and they want you to help with installing Git. 
### 1.	Write instructions on installing git on a windows system. Making sure to include
#### a.	What are the requirements to install Git on a system.
#### b.	If you had issues installing Git the workplace, give instructions on who you could you enquire about the installation disruption.
Git requirements:
- 1-2GB RAM
- 50mb storage
- Windows 7, 8, 8.1, or 10
- macOS 10.9 or newer

TO INSTALL:
- Go to the (official Git downloads page)[https://git-scm.com/downloads/win]
- Click on either the 64-bit or 32-bit version depending on your system
- Run the downloaded file to begin installation
- Read and accept the License agreement
- Choose an installation directory
- Click through next to accept the default configuration until you finish the setup
- Git is now installed on your Windows system

If any issues installing Git, please contact IT.
### 2.	Do research on some principles/techniques of industry standard best practices creating and working with repositories and branches in Git. 
#### a.	List the most important principles/techniques for creating and working with repositories
- Create a README file
- Frequent and small commits e.g. one bug fix per commit
- Consistent and clear commit names and descriptions
- Regularly push and pull changes to avoid merge conflicts
- Review changes before committing

Reference: [Best practices for repositories](https://docs.github.com/en/repositories/creating-and-managing-repositories/best-practices-for-repositories)
#### b.	List the most important principles/techniques for creating and working with branches
- Favor branching over forking
- Reserve the main branch for final changes and use development branches for actively working on the project
- Use consistent naming conventions for branches
- Pull from the main branch regularly to ensure you're working on up to date files
- Commit regularly
- If a branch is no longer used or is abandoned, delete it to keep a clean repository and reduce complexity
### 3.	List the steps in a Git workflow that the team should follow when working on projects.
- Set up the .gitignore when first initialising the repository
- Work on the local repository and make changes
- Commit regularly after each task is tackled (e.g. every bug fix)
- When ready to commit, check changes and name the commit clearly
- Work on different branches for separate lines of development, e.g. working on different features
- Merge changes from branches to main
- Push and pull changes regularly
