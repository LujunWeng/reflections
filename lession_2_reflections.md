###**What happens when you initialize a repository? Why do you need to do it?**
1. It creates the `.git` folder for this repository and creates no commit.
2. Because in this way `Git` can have what it should need to track the folder or the project.
3. `Git` creates a repository because it needs a specific entity to organise files.

###**How is the staging area different from the working directory and the repository? What value do you think it offers?**
The staging area contains files which will be committed in the next commit, while the working directory contains all the files and folders in the directory, and the repository is a collection that `git` operates on for version controls.

###**How can you use the staging area to make sure you have one commit per logical change?**
I can add files of same logical change into the staging area and make a commit. And then I can do the same thing to other files relating to other logical changes. In this way, I can create a neat commit history. 

###**What are some situations when branches would be helpful in keeping your history organized? How would branches help?**
One of classical scenario when a branch would be needed is when we are going to try to develop a new feature. Doing experimentals in a specified branch would avoid modifications on the master branch accidently.

Another classical situation is when we want to try a different path from the original one. So we have branches and get them developped parallelly.

###**How do the diagrams help you visualize the branch structure?**
From the diagrams, I can spot quickly how many branches there are and from which commit they are diverted. I can also have a clear thought of how my projects are organised now. And if I want to checkout any commit, the diagrams can help to find it quickly. 

###**What is the result of merging two branches together? Why do we represent it in the diagram the way we do?**
1. The result is a new commit that contains all the changes of two branches and makes one of the branch point to the new commit. Therefore, the updated branch contains the commit histories of both branches. 
2. It illustrates how we get this new commit -- that is how are two branches are merge, and how we get to other commits from the new commit.


###**What are the pros and cons of Git’s automatic merging vs. always doing merges manually?**
1. With manual merge, I can have what I tend to do precisely. That means I can have a clear understand of what I would get. However, this process might be time-consuming and tedious.
2. The automatic merging can relieve you from the boring process and doing merging automatically according to certain rules. But the disadvantage is also obvious. If two commits diff greatly, you would have lots of conflicts to deal with. Also, it's hard to imagine what it would be like of the new commit.