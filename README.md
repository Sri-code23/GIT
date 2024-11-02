Git Commands from Clone to Push:

# Clone a repository into a new directory, creating a local copy of the entire project.
clone: This command is used to create a local copy of a remote repository. It downloads the entire project and its history to your local machine.
# Command: 
### git clone <repository-url>

//////////////////////////////////////////////////////////////////////

# Add file contents to the staging area, preparing them for the next commit.
add: This command is used to stage changes made to files in your local repository. It prepares the files for the next commit.
# Command: 
### git add <file-name> /// git add . ( to add all changes )

//////////////////////////////////////////////////////////////////////

# Display the status of the repository, showing which changes have been staged, which haven't, and which files aren't being tracked.
status: This command is used to display the status of the repository. It shows which changes have been staged, which haven't, and which files aren't being tracked.
# Command: 
### git status

//////////////////////////////////////////////////////////////////////

# Record changes to the repository, creating a new commit with a meaningful message.
commit: This command is used to record changes made to files in your local repository. It creates a new commit with a meaningful message that describes the changes made.
# Command: 
### git commit -m "<commit-message>"

//////////////////////////////////////////////////////////////////////

# Add a remote repository to the local repository, allowing for collaboration and synchronization.
remote add: This command is used to add a remote repository to the local repository. It allows for collaboration and synchronization.
# Command: 
### git remote add <remote-name> <repository-url>  

// ex: ## git remote add origin https://github.com/Sri-code23/GIT.git   ////

//////////////////////////////////////////////////////////////////////

# Display information about the remote repository, including its URL and the branches it contains.
remote: This command is used to display information about the remote repository. It shows the URL and the branches it contains.
# Command: 
### git remote -v

//////////////////////////////////////////////////////////////////////

# Update remote refs along with associated objects, sending the committed changes to the remote repository.
push: This command is used to update the remote repository with the changes made in your local repository. It sends the committed changes to the remote repository.
# Command: 
### git push <remote-name> <branch-name>

//////////////////////////////////////////////////////////////////////
###      ###      ####     ####        ######       ######  ##  ######  ###  #### 
//////////////////////////////////////////////////////////////////////

Git Commands from Init to Push:

# Create an empty Git repository or reinitialize an existing one, setting up the necessary files and directories.
init: This command is used to create a new Git repository or reinitialize an existing one. It sets up the necessary files and directories for the repository.
# Command: 
### git init

//////////////////////////////////////////////////////////////////////

# Add file contents to the staging area, preparing them for the next commit.
add: This command is used to stage changes made to files in your local repository. It prepares the files for the next commit.
# Command:

### git add <file-name>

//////////////////////////////////////////////////////////////////////

# Display the status of the repository, showing which changes have been staged, which haven't, and which files aren't being tracked.
status: This command is used to display the status of the repository. It shows which changes have been staged, which haven't, and which files aren't being tracked.
# Command: 
### git status

//////////////////////////////////////////////////////////////////////

# Record changes to the repository, creating a new commit with a meaningful message.
commit: This command is used to record changes made to files in your local repository. It creates a new commit with a meaningful message that describes the changes made.
# Command: 
### git commit -m "<commit-message>"

//////////////////////////////////////////////////////////////////////

# Add a remote repository to the local repository, allowing for collaboration and synchronization.
remote add: This command is used to add a remote repository to the local repository. It allows for collaboration and synchronization.
# Command: 
### git remote add <remote-name> <repository-url>

//////////////////////////////////////////////////////////////////////

# Display information about the remote repository, including its URL and the branches it contains.
remote: This command is used to display information about the remote repository. It shows the URL and the branches it contains.
# Command: 
### git remote -v

//////////////////////////////////////////////////////////////////////

# Update remote refs along with associated objects, sending the committed changes to the remote repository.
push: This command is used to update the remote repository with the changes made in your local repository. It sends the committed changes to the remote repository.
# Command: 
### git push <remote-name> <branch-name>

//////////////////////////////////////////////////////////////////////