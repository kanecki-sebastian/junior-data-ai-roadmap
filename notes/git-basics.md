# Git workflow

    The basic Git workflow is:

    1. Edit files
    2. Check status
    3. Stage changes
    4. Commit changes
    5. Push changes to GitHub

# In commands:

    git status
    git add .
    git commit -m "Short description"
    git push

# The three important areas in Git

    1. Working directory

    This is where I edit files.

    2. Staging area

    This is where I prepare changes for the next commit.

    3. Local repository

    This is where Git stores committed changes on my computer.

    After that, I can push commits to the remote repository on GitHub.

# Important commands
    git status

        Shows the current state of the repository.

        It tells me:

        which files are changed,
        which files are untracked,
        which files are staged,
        whether there is anything to commit.

    git add .

        Stages all changed and new files in the current folder for the next commit.

    git commit -m "message"

        Saves staged changes into the local Git history with a descriptive message.

    git push

        Uploads local commits to the remote repository on GitHub.

    git log --oneline

        Shows a short version of the commit history.