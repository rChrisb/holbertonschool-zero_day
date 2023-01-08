# <p align=center> `Git` </p>
At the heart of GitHub is an open source version control system (VCS) called Git. Git is responsible for everything GitHub-related that happens locally on your computer.

## <p align=center>`Project's obejectives`</p>
Be able to explain:
* What is source code management
* What is Git
* What is GitHub
* What is the difference between Git and GitHub
* How to create a repository
* What is a README
* How to write good READMEs
* How to commit
* How to write helpful commit messages
* How to push code
* How to pull updates
* How to create a branch
* How to merge branches
* How to work as collaborators on a project
* Which files should and which files should not appear in your repo

## <p align=center>`Tasks` </p>


### <p align=center>`0. Create and setup your Git and GitHub account` </p>

---------------------------------------------------------------------------
### <p align=center>`1. Repo-session` </p>
Create a new directory called git in your repo.

---------------------------------------------------------------------------
### <p align=center>`2. Coding fury road` </p>
- Create these directories at the root of your project: bash, c, js
- Create these empty files:c/c_is_fun.c, js/main.js, js/index.js
- Create a file bash/best with these two lines inside: #!/bin/bash and echo "Best"
- Create a file bash/school with these two lines inside: #!/bin/bash and echo "School"
- Add all these new files to git
- Commit your changes (message: “Starting to code today, so cool”) and push to the remote server

---------------------------------------------------------------------------
### <p align=center>`3. Collaboration is the base of a company` </p>
For this project, create a branch update_script and in this branch:

Create an empty file named bash/98
Update bash/best by replacing echo "Best" with echo "Best School"
Update bash/school by replacing echo "School" with echo "The school is open!"
Add and commit these changes (message: “My personal work”)
Push this new branch Tips
Perfect! You did an amazing update in your project and it’s isolated correctly from the main branch.

Ho wait, your manager needs a quick fix in your project and it needs to be deployed now:

- Change branch to main
- Update the file bash/best by replacing echo "Best" with echo "This School is so cool!"
- Delete the directory js
- Commit your changes (message: “Hot fix”) and push to the origin


Ouf, hot fix is done!

---------------------------------------------------------------------------
### <p align=center>`4. Collaboration: be up to date` </p>
For this task – and only for this task – please update your file README.md in the main branch from GitHub.com. It’s the only time you are allowed to update and commit from GitHub interface.

After you have done that, in your terminal:

- Get all changes of the main branch locally (i.e. your README.md file will be updated)
- Create a new file up_to_date at the root of your directory and in it, write the git command line used
- Add up_to_date to git, commit (message: “How to be up to date in git”), and push to the origin

---------------------------------------------------------------------------
### <p align=center>`5. HAAA what did you do???` </p>
Collaboration is cool, but not really when you update the same file at the same time…

To illustrate that, please merge the branch update_script to main: “Cool, all my changes will be now part of the main branch, ready to be deployed!”

HHHHHHHAAAAAAAA

`CONFLICT (content): Merge conflict in bash/best`

As you can see, you have conflicts between two branches on the same file.

Your goal now is to resolve conflicts by using the version of the branch update_script, and push the result to the origin.

At the end, you should have all your work from the branch update_script (new file and two updated files) and all latest main commits (new files, delete folder, etc.), without conflicts.

---------------------------------------------------------------------------
### <p align=center>`6. Never push too much` </p>
Create a .gitignore file and define a rule to never push ~ files.

---------------------------------------------------------------------------

## <p align=right>`Score: 100/100` </p>
