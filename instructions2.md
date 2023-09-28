# Git and GitHub

## Individual

### Setup:
Open your terminal or command prompt.
Navigate to a directory where you'd like to create your new Git repository.

### Instructions:

1. Initialize a new repository
```git init```

2. Create a new branch
`git branch username-branch`

3. Switch branch
`git checkout username-branch`

4. Edit files

5. Stage
`git add .`

6. Commit
`git commit -m "message here..."`

7. Merge (from main)
`git checkout main`
`git merge username-branch`

8. Conflict resolution

9. Delete username-branch
`git branch -d username-branch`

10. List branches
`git branch`




## Collaborative

### Setup:
Open your terminal or command prompt.
Navigate to a directory where you'd like to clone the provided Git repository.

1. Clone the repository
`git clone <URL repo>`

2. Create a new branch


3. Add your contribution
Edit the README.md file

4. Stage and Commit

5. Push Your Changes
`git push -u origin username-branch`

6. Create a Pull Request in GitHub

7. Reviewing & Merging
Peer review the pull request. Read the story changes and leave a comment.
After reviewing, approve the pull request.
Once pull requests have been approved, merge them into the main branch. This will add the contributions to the main story.

8. Update Local Repository
After the pull requests are merged, update your local repository to get the latest version of the story.
`git pull`
`git branch -d platard-branch`
`git fetch --prune`

9. Conflict resolution
Update your main branch with the latest changes
`git pull`
Switch to the branch of the pull request
`git checkout username-branch`
Merge with the main
`git merge main`
Fix the conflicts and commit the result.
Push the changes

10. Delete username-branch

11. List branches