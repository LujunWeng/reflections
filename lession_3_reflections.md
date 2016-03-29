###**When would you want to use a remote repository rather than keeping all your work local?**
If there are several people working on a project at the same time, it would be best to use a remote repository and keep the remote up-to-date.
So if someone need the latest version of this project, he must pull the project from the remote repository first.
Also, if I am working on a project from different devices, then using a remote repository would be very helpful.

###**Why might you want to always pull changes manually rather than having Git automatically stay up-to-date with your remote repository?**

Basically, the remote repository is not always the latest version.

Usually, we would like make modifications locally and want to push changes to the remote repository. If Git automatically stay up-to-date with the remote, the local changes will disappear when sync with the remote.


###**Describe the differences between forks, clones, and branches. When would you use one instead of another?**
Forks and clones are similar to some extent. They both operate on repositories and can make a copy of another whole repository. But fork is invented by GitHub and used only in GitHub while clone is an operation of Git. Branches are totally different from them because branches operate on commits not repositories.

Forks are mainly used in GitHub when I want to get a copy of other people's project and clones are used when someone want to get a local copy from a remote repository or a local repository. As for branches, they are used to create different paths for a project so that if I want to try something new, the main path or branch wouldn't be affected.

###**What is the benefit of having a copy of the last known state of the remote stored locally?**
The most important benefit is that it provides us with the opportunity to compare the local version and the latest remote one, so we can make a decision of how to deal with differences.

###**How would you collaborate without using Git or GitHub? What would be easier, and what would be harder?**
Actually, I don't even think about collaborating with others. But I guess it would be quite harder without using Git or GitHub, mostly because we have no way to keep track of each modifications and we would have tough time to merge our different versions into one version. 
