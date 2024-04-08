# Collaboration with git

In this workshop we'll tryout various common techniques for collaborating on a software development project using git.

The more "real" your example code is, the more authentic issues you'll run in to. (ie when you make a commit, don't just change a single line. Make a real change that spans multiple files and actually acomplished something)

## 0. Create a shared repository
One person in each group does the following:

1. Create a public repository for the workshop
    * Tick the `Add a readme` checkbox to get an initial commit and a default `main` branch
1. Invite the others as collaborators (settings -> collaborators)

## 1. Clone the project locally
Everybody in the group can now clone the repository and see the same initial commit. Everybody is also automatically linked to the same remote repository.

## 2. Experiment
Take the opportunity to experiment and really try to get in sticky situations in this repository so that you have experienced it before once it happens in your real project.

Examples of things to try

### Common operations
Use VS Code to perform common operations
* Make commits and try the following
    * Commit all changes
    * Stage only some of the edited files
    * Stage selected sections in a file
* Work with branches
    * Create branches
    * Make commits in different branches
    * Checkout different branches and see how the files in you project updates accordingly
    * Try to merge branches
    * Try to rebase

### Working directly in main
* Have everybody work (in parallell) and commit to directly to `main`. Push, and try to get all code merged.

### Working in separate branches
* Have everybody work in separate branches. Try to get all code merged into main.

* If you like, try to do a rebase in order to get your feature-branch in synch with `main`:
    * In `main` pull the changes from github 
    * Switch to you own branch and do a rebase

### Conflicts
* If you haven't already: Setup a situation were you'll get a merge conflict. Resolve it.

### Pull requests
* Make something in a separate branch. 
* Push the branch to github
* Open github in the browser and create a pull request.