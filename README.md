# Hello DDMAL newcomers!
## This is a simple git activity: Add your names to a LICENSE file

### Rules

The `master` branch is blocked! You can’t push anything there, but you can create a `develop` branch and add your changes there!

> Hint: Clone the repo, get into the right branch (develop), make your changes, push them back into the remote repository (remember the default name for remote repositories?)

We will randomly decide the order in which the names should appear

We conclude when everyone has added their own name to the LICENSE

*You can use a placeholder for your name (e.g., BATMAN), but you should effectively contribute with your commit to the repository*

### Procedure

1. First contributor: The `develop` branch does not exist yet, your task is to create it. In that branch, append your name to the LICENSE around the **Copyright** statement and push that branch into the remote repository
2. Everyone else before the last contributor: Pull the latest version of the `develop` branch, then, append yourself to the LICENSE file. Finally, push back the changes to the remote repository
3. Last contributor: Repeat the same procedure as everyone else, however, once you push the changes to the `develop` branch, within the GitHub web interface, make a pull request to merge the changes into the `master` branch. Make sure that the content of the LICENSE is correct before doing the pull request, otherwise it may be rejected by the admin of the repo!

### Tips

After you clone a repository, you can get the latest commit of a remote branch by running the command
```
git checkout <remote_repo_name>/<remote_branch_name>
```

Then, you can create a local version of that branch with the following command
```
git checkout -b <local_branch_name>
```

You can use this, for example, to get what has been pushed to the remote `develop` branch, make changes to that branch in your local version, commit the changes, and push them back to the remote branch
