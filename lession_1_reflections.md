###**How did viewing a diff between two versions of a file help you see the bug that was introduced?**
It can help to find out what has been modified easily between the stable version and the one, which introduced the bug. So I can narrow down the range of potential places that caused the bug.

###**How could having easy access to the entire history of a file make you a more efficient programmer in the long term?**
Fistly, it can show all the modifications you have made and help you to narrow down the places where bugs might be introduced. Secondly, I think it is easy to forget what I did or thought several days ago. So the history can help to review what I have done and thought. Thirdly, if somebody comes to help you with your bugs and he/she has the entire history, it would be easier to help you to solve your problems. 

###**What do you think are the pros and cons of manually choosing when to create a commit, like you do in Git, vs having versions automatically saved, like Google Docs does?**
The most important pro is that we can choose to create a commmit whenever we want to, which means we could have a easy-understanding commit history. It can help us to review what we have done and spot bugs more easily. 

On the other hand, the disadvanges are also obvious, compared to automatically committing. We need to have a good judgment to determine when to commit, or we would make commit history a mess and hard to understand. Sometimes, we might forget to commit, which is bad because we don't always have a good memory. 

###**Why do you think some version control systems, like Git, allow saving multiple files in one commit, while others, like Google Docs, treat each file separately?**
It is because in some cases multiple files are related to each other. Modifying one file will affect other files and they together with other files form a entire project. Therefore it would be very difficult for reviewing if commit doesn't contain files' modification details. However, most files saved in systems like Google Docs are unrelated. They are self-contained. So they can be saved seperately. 

###**How can you use the commands git log and git diff to view the history of files?**
I can use `git log` to view the history of commits of this repository, and then If I want to know what has been changed in files between commits, I can pick up those commits' IDs in the output of `git log` and use `git diff` to get the differences. 

###**How might using version control make you more confident to make changes that could break something?**
If I create commits effectively, then I would not be afraid of breaking something when I make changes. Because whenever I want, I can roll back to previous versions that work correctly. 

###**Now that you have your workspace set up, what do you want to try using Git for?**
I want use Git to track my notes and I also want to start up a toy project to learn more about Git.