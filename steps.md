## GitHub and Visual Studio Code

##### 1-Opening Project
Open a project in Visual Studio Code. Open terminal in the respective directory.

##### 2-Check for Git version
Type `git --version` in the terminal to look if git is installed or not. If not, install it from [https://git-scm.com/downloads](https://git-scm.com/downloads)

##### 3-Update Username or Email
Type `git config --global user.name "YOUR USERNAME"` to add up username. Same goes for email with `user.email` in place of `user.name`.

##### 4-Check state
See if you are signed in by `git config --global --list`. This will show up your username which is a sign for you  have logged in.

##### 5-Initialise a repository
`git init trial_proj` will create a repository locally of the name trial_proj

##### 6-Committing your first tries
For an already created file, tap the `+` icon for the file shown in the Source Control Tab (Ctrl+Shft+G) also called the Git Tab for files you want to commit changes.
Tapping the plus icon for particular filr is called staging the file and after every staging you need to enter a message(optional) and then press the tick at the top. This is the most needed quality of locally handled git.

##### 7-Verify commitment
To check if its committed, type `git log` and press Enter, or click Timeline dropdown to see steps just taken.

##### 8-Pushing this to a remote repo
Create a repo in on your github acccount. Creating will also show you codes to do further steps, where we have almost completed half of the steps. Push your repo in by git remote add origin "your_repo_link" and then git push -u origin master. This will ask for credentials and you are done! Check for your files in the repository on your browser. To keep on uploading and downloading changes, just use the circular refresh button at the bottom left corner of Visual Studio Code present at the right side of "master" button. You can also use git push -u origin master again to push changes.

##### 9-Pulling changed files
If someone has worked on your files, or if you have changed it over github on the browser, you can pull the files by clicking on the three-dots on the top of Source Control Panel.

These are the basic steps to use GitHub with Visual Studio Code. Add up more amazing things below if you want to share!!!









