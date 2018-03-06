Hi there, this is intended to be a git hub demo project where I put it to this repository on GitHub following the process below:(Assumption is that the mvc project is already created in Visual Studio with all the associated files/folders for putting to the repository)
Downloaded and installed git bash from the following URL:
https://git-scm.com/download/win
Brought up the Git Bash Window (in Windows 10 from start menu)
Changed the directory to the working directory of the project by cd command
Issued the command 'git init', to initialize a new repository (on local folder). it gave the output 'Initialized empty Git repository in...'(... means the local path) 
Added all the files (for staging to the repository) following this command : git add . 
Checked the status of the branch with command 'git status' (The out put was 'On branch master No commits yet'
'Changes to be committed'(followed by a list of all the new files that need commit as follows):
 new file:   .gitattributes
        new file:   .gitignore
        new file:   GoogleMaps.sln
        new file:   GoogleMaps/App_Start/BundleConfig.cs
        ..................
        ..................
        ...................
Now all the above new files were commited (including commit message) by the command:
 git commit -m 'Initial Commit to Github'
 The command in step 18 produced output as:
 [master (root-commit) db2002b] Initial Commit to Github
 45 files changed, 27635 insertions(+)
 create mode 100644 .gitattributes
 create mode 100644 .gitignore
 create mode 100644 GoogleMaps.sln
 create mode 100644 GoogleMaps/App_Start/BundleConfig.cs
 create mode 100644 GoogleMaps/App_Start/FilterConfig.cs
 create mode 100644 GoogleMaps/App_Start/RouteConfig.cs
...................
...................
A new remote repository was created after logging on to to Github at https://github.com/
The new repository URL was then copied by clicking 'Clone or download' button at 'https://github.com/krchome/GitDemo' (Here 'krchome' is the username and 'GitDemo' the repository name.)
The remote repository was added to Gitbash using the command :  git remote add origin https://github.com/krchome/GitDemo.git
Fijnally the changes were pushed to the remote repository using the command:
$ git push -u origin master

Note: The above steps list the bare minimum needed to push local changes to a remote repository for automatic version control and sharing. Please be aware that the above list of commands are by no means comprehensive and there are many more to use under different circumstances. 
Refer to the link: https://git-scm.com for all the documentation. 
I also found this link useful: https://www.youtube.com/watch?v=Y9XZQO1n_7c
