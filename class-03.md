# Class 03 - Git


# What is GitHub?

Github is a hub focused tool which allows users to interact and manage files with other users. It is the largest host of Git repositories and it is used by many developers all over the world.

It is fundamentally a way to share open-source projects with other developers/whoever may want to see.

## A general idea of the GitHub workflow;

1. Create a specific topic branc from the master source.
2. You then commit (add) the changes for the project.
3. You can then push the specific topic branch to your project.
4. You can then open a pull request to pull other data from somewhere else.
5. If applicable, you may speak to your team members and perform other commits.
6. The project owner then closes/merges the pull request.

# What is Git?

- Git is a DVCS (Distributed Version Control System), which stores data made up of 'snapshots'. Each time in which you save (commit) a file, Git creates a 'snapshot' of it and stores a reference.

- It mainly relies on local operations because the information which is needed can be found on your local resources.

- Every single change which is made is tracked by Git.

- It is setup in a way that greatly reduces the chances of damage to your files, such as an accidental loss of data.

## Files on Git can be in 3 different states;

- Commited (Data is secured in a local database)
- Modified (File has had changes made to it but its not been commited (added)
- Staged (It has been flagged to be commited in the next snapshot)

# What is Terminal?

The terminal is a text-based interface on the computer. You may type commands, change files, execute programs, open different project files etc. When you are working in the terminal, it is called your 'Working Directory'.

For example, if I wanted to add a new directory in my folder without right-clicking and adding new file, I could type in the terminal;

mkdir New Folder

This would then create a new directory called 'New Folder'

# ACP 

- Add: Add a file to the repository by using command, 'git add .'
- Commit: Commit your changes (save) by using command, 'git commit'
- Push: Push your changes onto the branch specfic, 'git push'

If you need to check your branch then you can use the command, 'git branch'

These are the 3 stages of workflow, first you add a new file, then you commit (save), then you push it onto the main when you are completely finished.
