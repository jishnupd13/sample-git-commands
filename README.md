# sample-git-commands
sample demo for git

<h4>Sample Git Commands</h4>

<b> These are sample git commands that used in version control system </b>

<h6>git init </h6> 

This command is user to initialize the git into your project. This command is used to create a blank git repository.Not also this command is used to convert your existing project 
to git project.

<h6>git add  filename</h6> 

This command is used to adding the files that you update or newly created in to the git.Not also without add the files you cannot do any further operation in git.For adding a single
file you can use <h5>git add test.txt</h5> or multiple files you can do this <h5>git add text.txt hello.txt</h5> or if you can add all files use <h5>git add .</h5> or <h5>git add --all</h5>

<h6> git commit -m "message" </h6>

The "commit" command is used to save your changes to the local repository. Note that you have to explicitly tell Git which changes you want to include in a commit before running the "git commit" command. This means that a file won't be automatically included in the next commit just because it was changed.

<h6> git status </h6>

The status command tells the user to the state of current working directory eg : which files tracked ,which files untracked etc.

<h6>git log</h6>

This command shows the commit history that occured in the project in chronological order (the most recent commits first)

<h6>git remote add  remote_alias_name(origin) https url</h6>

This command is user to link your local repository to the remote server.We can use remote server service from github,gitlab or big bucket.

<h6> git branch branch name </h6>

This command is used to add a new brach in a git project.Default branch is always master branch eg: <h7>   git branch login_module   <h7> If you are type git branch without branch name
it shows current working branch.

<h6>git push remote_name(origin) branch_name</h6>

This command is used to push the code to the remote server (github,gitlab,big bucket) after a successfull commit

<h6>git merge branch_name</h6>

 The git merge command lets you take the independent lines of development created by git branch and integrate them into a single branch. Note that all of the commands presented below merge into the current branch.

<h6>git pull branch_name</h6>

The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content
