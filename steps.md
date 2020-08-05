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

