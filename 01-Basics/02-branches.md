# Git: Basics

</br>

## Branches

Git **branches** are pointers to commits. They allow for multiple versions of the main repo to be worked on simulataneously.

To create a new branch, first make sure that you're in the `main` branch and run the following command from your terminal:

`git branch <branch_name>`
`git checkout <branch_name>`

OR

`git checkout -b <branch_name>`

</br>

![commit chain](../public/new-branch.png)

</br>

## Merging Branches

In git, **merging** branches is a way of combining two separate branches into one repository. This allows for multiple developers to _branch off_ from the main repo and combine features at a later time.

Merging a commit from a branch creates two unique parents.

</br>

![commit chain](../public/merging1.png)

</br>

![commit chain](../public/merging2.png)

</br>

From the terminal under the `main` branch, run the following command:

**`$ git merge bugFix`**

![commit chain](../public/merging3.png)
