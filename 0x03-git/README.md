# 0x03. Git
## Resources
Read or watch:
- [Resources to learn Git](https://docs.github.com/en/get-started/getting-started-with-git/set-up-git)
- [About READMEs](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes)
- [How to write a Git commit message](https://cbea.ms/git-commit/)

Resources for advanced tasks 

- [Learning branching](https://learngitbranching.js.org/)
- [Effective pull requests and other good practices for teams using GitHub](https://codeinthehole.com/tips/pull-requests-and-other-good-practices-for-teams-using-github/) 
# Tasks
## 0. Create and setup your Git and GitHub account
Step 0 - Create an account on GitHub 

Step 1 - Create a Personal Access Token on Github

You can follow [this tutorial](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens) to create a token.

Step 2 - Update your profile on the Intranet
Update your Intranet profile by adding your Github username 

Step 3 - Create your first repository
Using the graphic interface on the github website, create your first repository.
- Name: alx-zero_day
- Description: I'm now a ALX Student, this is my first repository as a full-stack engineer
- Public repo
- No README, .gitignore, or license


Step 4 - Open the sandbox
Once the container is started, click on  to open a shell where you can start work from.

Step 5 - Clone your repository
On the webterm of the sandbox, do the following:
Clone your repository

Step 6 - Create the README.md and push the modifications
Navigate to this new directory. [Tips](https://askubuntu.com/questions/232442/how-do-i-navigate-between-directories-in-terminal)

Create the file README.md with the content My first readme. [Tips](https://forum.howtoforge.com/threads/echo-into-a-file.115/)                                                                                                                

Update your git identity

Add this new file to git, commit the change with this message “My first commit” and push to the remote server / origin



## 1. Repo-session
Create a new directory called 0x03-git in your alx-zero_day repo.

Make sure you include a not empty README.md in your directory:

at the root of your repository alx-zero_day
AND in the directory 0x03-git

## 2. Coding fury road


For the moment we have an empty project directory containing only a README.md. It’s time to code!
Create these directories at the root of your project: 

bash, c, js

Create these empty files:

- c/c_is_fun.c
- js/main.js
- js/index.js

Create a file bash/alx with these two lines inside: 

#!/bin/bash and echo "ALX"

Create a file bash/school with these two lines inside: 

#!/bin/bash and echo "School"

Add all these new files to git
Commit your changes (message: “Starting to code today, so cool”) and push to the remote server

## 3. Collaboration is the base of a company
For this project, create a branch update_script and in this branch:

Create an empty file named bash/98

Update bash/alx by replacing echo "ALX" with echo "ALX School"

Update bash/school by replacing echo "School" with echo "The school is open!"

Add and commit these changes (message: “My personal work”)

Push this new branch Tips
Perfect! You did an amazing update in your project and it’s isolated correctly from the main branch.

Ho wait, your manager needs a quick fix in your project and it needs to be deployed now:

Change branch to main

Update the file bash/alx by replacing echo "ALX" with echo "ALX School is so cool!"

Delete the directory js

Commit your changes (message: “Hot fix”) and push to the origin

 ## 4. Collaboration: be up to date
Update your file README.md in the main branch from GitHub.com. 
After you have done that, in your terminal:

Get all changes of the main branch locally (i.e. your README.md file will be updated)

Create a new file up_to_date at the root of your directory and in it, write the git command line used

Add up_to_date to git, commit (message: “How to be up to date in git”), and push to the origin 

## 5. HAAA what did you do???
Merge the branch update_script to main: 
“Cool, all my changes will be now part of the main branch, ready to be deployed!”

HHHHHHHAAAAAAAA
CONFLICT (content): Merge conflict in bash/alx

As you can see, you have conflicts between two branches on the same file.
Your goal now is to resolve conflicts by using the version of the branch update_script, and push the result to the origin.
At the end, you should have all your work from the branch update_script (new file and two updated files) and all latest main commits (new files, delete folder, etc.), without conflicts. 

## 6. Never push too much


Create a .gitignore file and define a rule to never push ~ files (generated by Emacs). [Tips](https://git-scm.com/docs/gitignore) 

