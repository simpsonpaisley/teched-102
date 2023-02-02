# Class 03 Reading Notes

## Git and Github

### What is Git?

Git is the dependency for GitHub, this means it must be installed on your computer so you can push code to GitHub from your computer, using the terminal.

### What is GitHub?

GitHub is a platform for versioning control. This means you can go back to older versions of your code if needed. You can also see any changes made, and it also allows you to collaborate with other developers. 

### The Git ACP Process

The Git ACP process is the process you should use when pushing code to GitHub. ACP stands for:

- **A** - `git add`. This adds any changes to the staging area. You can use `git add .` to add all changes.
- **C** - `git commit -m "Message"`. This captures a snapshot of the repository at that moment. You should always add a message to the commit to let people know what changes you have made.
- **P** - `git push` - This pushes the changes from the staging area into production. You can use `git push -u origin main` to push the changes to the main branch.

### Pull Requests and Forks

If you would like to work on someone else's code, you can fork their repository. This creates a copy of their repository in your GitHub. You can then make changes without changing the code in their repository.

If you would like to suggest the changes to the creator's repository, you can submit a pull request. This allows them to see the changes you have made, and push it to their own repository if they would like. 