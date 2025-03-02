Git Commands

// Setting Username
1.git config --global user.name "Name"
.git config --global user.name
// Setting Usermail
2.git config --global user.email "Email"
.git config --global user.email

3.git status //list down all modified or newly added files/folders or changes made
4.git branch // list down all available branches

// Reading and Writing/Updating Commands

5.git clone repo_url // Cloning or Copying repository from github

// Pushing Changes or newly modified files to remote repository
6.git add . // All modifieed files/folders to the Staging area(files ready to added to remote)
7.git commit -m "Initial Commit" //Files/folders which are ready to be pushed to the remote repository
8.git push origin BRANCH_NAME // for pushing local changes to the remote repository

// Creating new branch
git branch BRANCH_NAME // create a branch
git checkout BRANCH_NAME // Select or gets into the specified branch 

git pull origin BRANCH_NAME // Pulling latest changes from remote repository to local repository