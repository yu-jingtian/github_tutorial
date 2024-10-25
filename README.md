# github_tutorial
A github tutorial for fellow PhD Students at Oregon State University

## Forking an existing repository: 

Forking: Make a copy of someone's public github repository to your own account.

- Fork this repository! 
- Clone the repository to your local machine: 
Find the green "<> Code" button, and copy the URL 
This will copy the repository to your local machine. 

Open R Studio, 
File, New Project, Version Control, Git, paste the URL in the "Repository URL" box.

You now have a local copy of the repository on your machine.

### Make some changes!

A README file is useful! It will render as the main page on GitHub. Useful for explaining what your project is, how to use it, and what is contained. 

Write something here, or correct my typo!
Save file 

### Version control: How/why
You've made a change. Now you want to confirm you made a change, document that you have made a change, and save the change remotely. 

Make sure you have the most updated version of the project: git pull
- Gets the version of the project on GitHub

Confirm you made a change: Git add 
- Adds the saved version of the file to the staging area

Document you made a change: Git commit
- Commits the changes locally with a description of what you did

Save the change remotely: Git push
- Pushes the changes to the remote repository


#### Option 1: Use R Studio's git interface
- Go to the Git tab in the upper right hand corner of R Studio
- Check the box next to the file you want to commit
- Write a commit message in the box at the top of the Git tab
- Click "Commit"
- Click "Push" to push the changes to the remote repository


#### Option 2: Command line 
- Open a terminal
- Navigate to the repository
- `git add .`
- `git commit -m "Your message here"`
- `git push`

## Important for stats projects: Git ignore: 
Github will track everything in your repository, including data files. This is not good!
If you have HUGE simulation files, this will usually break push/pull/tracking 

Add any private data files and simulation folder items to the .gitignore file.

Add a simulation folder to the project. 

Don't track anything the simulation folder might contain to the .gitignore file by adding 
`Simulation/`

Save your .gitignore change and add/commit/push to your repository 

Test it works! 
Add a file in that folder, and try to push it to the repository. Will it show up?

## Branches: How you are supposed to use Git/Github (but I don't always tbh)
What are branches for?
- Main branch: Stuff you know works
- Branches: Stuff you are working on, but don't want to mess up what you know already works 
- Branches are a way to work on a project with other people without conflicting


- Create a new branch:
`git checkout -b new_branch_name`
- Make some changes
- Commit the changes 


- Push the branch to the remote repository
`git push --set-upstream origin branch_test`


- View the differences on GitHub and if you like the changes, merge the branches
- Create a pull request 
- Merge the branch to the main branch

- Return to the main branch and pull from github

## Keep track of what you have done
- Commit messages and Diff files!
- Commit messages should be informative and concise
- Diff files show what you have changed in a file
- Use these tools to keep track of what you have done and why you have done it


- Add and commit are local 
- Push and pull are to Github 

## Make your own repository: - Github pages!

https://pages.github.com/

Students get free github education, which includes the ability to have private repositories (and github copilot). 

In general when making a repository, keep in mind: 
- Add a README.md file
- Decide on private/public
- Add a .gitignore file, using the R settings
- Add a license 

You can make one website based on your username, if you create a new repository titled 
`username.github.io`


You can turn any repository into a website


(This repository is actually a github site!)
https://empalmer.github.io/github_tutorial/

## Resources: 
A great 
https://docs.github.com/en/get-started/start-your-journey/hello-world