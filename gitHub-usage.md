# GitHub

GitHub is a Git version manager.

Why use a version control repository?

- Work with others ;
- Collaborate on open source projects ;
- Keep a history of your project ;
- Be able to find out who made each change;
- Know why each change was made.

## Tools to download to facilitate working with GitHub and Markdown

- [Atom](https://atom.io): Text editor.
- [GitHub Desktop](https://desktop.github.com): Facilitate management of Git.

## Create a GitHub account

GitHub is an online service that allows you to host your remote repositories.
To create your GitHub account, go to the home page [GitHub](https://github.com), click on Sign up. You will then be asked to fill in a username, an email and a password.
![Sign up view](/image/sign-up.png)
Then, choose the free subscription.

## Git management

### Overview of repository management
![Git working overview](/image/git-repository.jpg)

### Good practices of work 
- Initiate your local repository, thanks to git clone. 
- When beginning to work, always make a pull to update your local repository according to the remote one.
- After each sub-task done, commit your changes on your local repository.
- Before to stop to work, always push your work on the remote repository.

## Principle of Git

### Overview of version and branch management
![Branch overview](/image/branch.jpg)

The main branch is the clean version of your project.
The other branches created from the main branch are working branches that allow you to perform tasks in parallel in a collaborative project.

### GitHub Desktop to manage repository and branches

GitHub Desktop:
![GitHub Desktop](/image/github-desktop.jpg)

Repository management:
![Repository management](/image/repository-management.jpg)

Branch management:
![Branch management](/image/branch-management.jpg)

### Good practices of work with branch

- Create a working branch to address a task
- Merge management:
    - After having pushed your local branch to the remote one, merge the main branch into your branch.
    - Solve conflicts, if needed.
    - Commit, Push.
    - Pull request (query to merge your branch into the main branch).

### Conflict management

When you merge two branches, some conflicts can appear. Use Atom to open files with conflicts.

Atom will show you the two versions that have not succeed to be merged automatically.
The two versions will be highlighted in two different colors and as follows:
````
Use me
>>>>>>>
your version
<<<<<<<

Use other
>>>>>>>>>
The other version
<<<<<<<<<
````

Observe the two versions, choose one of them or create the suitable version by integrating changes made in the two versions.
Then, remove conflict delimiting chevrons.
Commit the files by indicating "Conflicts are solved" as message, and push.


## Project management: Collaborative work with GitHub

Milestones and issues management in GitHub

