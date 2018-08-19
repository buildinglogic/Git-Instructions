# Hello-world

Begin of github
Get used to github from today

try to modify the readme from "readme-edit" bracnch




# Add / connect to remote  

In Terminal, add the URL for the remote repository where your local repository will be pushed.

$ git remote add origin remote_repository_URL
// Sets the new remote as "origin"

$ git remote -v
// Verifies the new remote URL

Push the changes in your local repository to GitHub.

$ git push -u origin master
// Pushes the changes in your local repository up to the remote repository you specified as the origin



# create / checkout /delete branch  


Create the branch on your local machine and switch in this branch :

$ git checkout -b [name_of_your_new_branch]

Change working branch :

$ git checkout [name_of_your_new_branch]

Push the branch on github :

$ git push origin [name_of_your_new_branch]



# Check out remote branch

show all branches (local and remote)
$ git branch -a

show only remote branches
$ git branch -r

show the connect and branch you are
$ git remote show origin


//To fetch a branch, you simply need to:

git fetch origin

//This will fetch all of the remote branches for you. With the remote branches 
//in hand, you now need to check out the branch you are interested in, giving 
//you a local working copy:

git checkout -b test origin/test


# Delete branch

To delete a local branch:
$ git branch -d the_local_branch




