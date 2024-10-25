# github_tutorial
A github tutorial for fellow PhD Students at Oregon State University


## Step 1 
Forking an existing repository: 

- Fork this repository! 
- Clone the repository to your local machine: 
Find the green "<> Code" button, and copy the URL 
This will copy the repository to your local machine. 

Open R Studio, 
File, New Project, Version Control, Git, paste the URL in the "Repository URL" box.

You now have a local copy of the repository on your machine.

### Make some changes!

Write something here, or correct my typo!
Save file 

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


## Branches: How you are supposed to use Git/Github (but I dont always tbh)
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


## Keep track of what you have done
- Commit messages and Diff files!
- Commit messages should be informative and concise
- Diff files show what you have changed in a file
- Use these tools to keep track of what you have done and why you have done it


## Test 2 
Make your own repository: 
Good things to do: 
- Add a README.md file
- Add a .gitignore file, using the R settings
- Add a license 


## Resources: 
A great 
https://docs.github.com/en/get-started/start-your-journey/hello-world