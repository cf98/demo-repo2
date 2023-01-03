## demo-repo 2

Some new text.

To push local git repo to github. Easiest way is to create one in github.

```zsh
git remote add origin git@github.com:cf98/demo-repo2.git
```

Git hub renamed master branch to main, so that I need to use main.
```zsh
git push origin main
```

To add something like a shortcut to this: `git push -u origin main`, then in the future I can just use `git push`

Need to save the file to allow git status to detect it.

## branching.
* each branch only keeps changes on its own.
* works on feature branch before merge with the main branch.
* `git branch` shows branches.
* `git checkout -b feature-readme-instructions` will show the branches.
* to change back: `git checkout main`

## local development
1. open index.html in your own browser.


## New notes
`git push -u` equals `git push --set-upstream origin`

pull request is to have code pulled to a different branch.