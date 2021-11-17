GITHUB Tutorial
===============

### GIT workflow :
Add, Commit, Push
1. You modify a file from the working directory
2. You add these modified files to the staging area (add)
3. You perform the commit operation that moves the files from the staging area (commit)
4. You push the new changes, it stores the changes permanently to the GITHUB repository (push)

#### Two ways of using GIT :
1. By using the CLI (Command Line Interface, with the CMD from windows)
2. By using GitHub Desktop (see: [GitHub Desktop](https://desktop.github.com/))

> Easiest way is to use GitHub Desktop, as there will be no need to use the add, commit and push command everytime you want to update your project

#### Get your project up and running :
- Pre-requisites, download [GIT](https://git-scm.com/downloads) and [GitHub Desktop](https://desktop.github.com/)
- Side note, when installing GIT, hit "next" on all the steps, no need to change anything there.

1. Go to [GitHub](https://github.com/)
2. Create an account
3. Launch GitHub Desktop
4. Sign in with your GITHUB credentials
5. In the menu bar, click on File -> New Repository
6. Fill the name field, no need for a description. Check the "Initialize this repository with a README" checkbox, no need for a git ignore or license, choose the path of the repository where all files and folders will be uploaded (Local Path), remember the path after creation.
7. Once created, publish the repository on GITHUB (blue button in GitHub Desktop)
8. Repository is created.

#### Depending on who is responsible for the project, that person needs to upload the existing files onto the repository
- Do that by dragging the files and folders into the repository's directory (the local path that was used during the creation process)

#### When the new files and folders have been added, go back to GitHub Desktop and there should be all the new items listed
- Now's the time to commit :
1. Under the list of files, fill in the Summary field (name of your commit), description is not mandatory
2. Click on "Commit to main", "main" being your active branch
3. Once completed, clic on the blue button "Push origin", this will upload the files onto GitHub

#### To work as a group on the same repository/project :
- Repository's owner should go on their repository page -> Settings -> Manage Access (left sidebar, second option) -> Add People (Collaborators)
- Add the people who are in the group by filling in their github's username, full name or email
- The invited people will have to accept the invitation, make sure to check notifications or email.
- Once accepted, the members will have the "push" access to the repository and will be able to add, delete, modify the repo's files

When working as a group on a project :
- Be careful as to what you're editing, if two people work on the same file, "conflicts" will appear
- Try to always create a new branch when working on a new functionality, this will prevent conflicts, give a structure to your repo's workflow and be clearer
- Try to have one person in your group who checks the code for conflicts or code errors, that person will be responsible for adding the new commits onto the repository, adding a new layer of security against bugs, errors and conflicts


