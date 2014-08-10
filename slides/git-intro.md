![Git](http://www.rosehosting.com/blog/wp-content/uploads/2014/05/how-to-install-and-set-up-git-on-ubuntu-14-04-lts-vps.jpg)
#Git intro

### [Mengxin Zhu](mailto://zhumxin@cn.ibm.com)

### Rev. 1.0



#History

### Git was initially designed and developed by Linus Torvalds for Linux kernel development in 2005

### Latest stable release 2.0.4 (30 July 2014)

Note:Git development began after many developers of the Linux kernel gave up access to BitKeeper, a proprietary SCM system that had previously been used to maintain the project.[8] The copyright holder of BitKeeper, Larry McVoy, had withdrawn free use of the product after claiming that Andrew Tridgell had reverse-engineered the BitKeeper protocols.
Torvalds wanted a distributed system that he could use like BitKeeper, but none of the available free systems met his needs, particularly in terms of performance. Torvalds took an example of an SCM system requiring thirty seconds to apply a patch and update all associated metadata, and noted that this would not scale to the needs of Linux kernel development, where syncing with fellow maintainers could require 250 such actions at a time. He wanted patching to take three seconds,[4] and had several other design criteria in mind:
take Concurrent Versions System (CVS) as an example of what not to do; if in doubt, make the exact opposite decision[6]
support a distributed, BitKeeper-like workflow[6]
very strong safeguards against corruption, either accidental or malicious.[5]
These three criteria eliminated every then-existing version control system, except for Monotone. Considering performance excluded this too.[6] So immediately after the 2.6.12-rc2 Linux kernel development release,[6] Torvalds set out to write his own.[6]
Torvalds has quipped about the name git, which is British English slang roughly equivalent to "unpleasant person". Torvalds said: "I'm an egotistical bastard, and I name all my projects after myself. First 'Linux', now 'git'."[9][10] The man page describes git as "the stupid content tracker".[11]
The development of Git began on 3 April 2005.[12] The project was announced on 6 April,[13] and became self-hosting as of 7 April.[12] The first merge of multiple branches was done on 18 April.[14] Torvalds achieved his performance goals; on 29 April, the nascent Git was benchmarked recording patches to the Linux kernel tree at the rate of 6.7 per second.[15] On 16 June Git managed the kernel 2.6.12 release.[16] Torvalds turned over maintenance on 26 July 2005 to Junio Hamano, a major contributor to the project.[17] Hamano was responsible for the 1.0 release on 21 December 2005, and remains the project's maintainer.[18]



#Git popularity


##Companies & Projects Using Git
![Companies & Projects Using Git](https://www.evernote.com/shard/s220/sh/13bce916-ed45-44da-b824-de32587a3dca/8627f5be1fe866ff040f218d522eaa42/deep/0/Git.png)


##Git as Development tool
![Dev tool landscape for 2014](http://zeroturnaround.com/wp-content/uploads/2014/05/2014-leaderboard-of-java-tools-and-technologies-640x453.jpg)

[more read](http://zeroturnaround.com/rebellabs/java-tools-and-technologies-landscape-for-2014/)



#How Git inspires the innovation


#Social coding


![site logo](https://openframework.stanford.edu/sites/default/files/githuboctocat.jpeg)

* 5 July 2009, 100,000 users mark
* 25 July 2010, 1 million repositories
* 20 April 2011, 2 million repositories
* 16 January 2013, 3 million users mark and 5 million repositories
* 23 December 2013, 10 million repositories
* July 2012, Andreessen Horowitz invested $100M in venture capital

Note:GitHub is a Git repository web-based hosting service which offers all of the functionality of Git as well as adding many of its own features. Unlike Git, which is strictly a command-line tool, Github provides a web-based graphical interface and desktop as well as mobile integration. It also provides access control and several collaboration features such as wikis, task management, and bug tracking and feature requests for every project.[3]
GitHub offers both paid plans for private repositories, and free accounts, which are usually used to host open source software projects. As of 2014, Github reports having over 3.4 million users,[4] making it the largest code host in the world.[5]
GitHub has become such a staple among the open-source development community that many developers have begun considering it a replacement for a conventional resume and some employers require applicants to provide a link to and have an active contributing GitHub account in order to qualify for a job.[6][7]
24 February 2009: GitHub team members announced in a talk at Yahoo! headquarters on that during the first year that GitHub was online, it accumulated 46,000 public repositories, 17,000 of them in the previous month alone. At that time, about 6,200 repositories had been forked at least once and 4,600 merged.
5 July 2009: a GitHub Blog post announced that they had reached the 100,000 users mark.
27 July 2009: In another talk delivered at Yahoo!, Tom Preston-Werner announced that GitHub had grown to host 90,000 unique public repositories, 12,000 having been forked at least once, for a total of 135,000 repositories.[15]
25 July 2010: GitHub announced that it hosts 1 million repositories.[16]
20 April 2011: GitHub announced that it is hosting 2 million repositories.[17]
9 July 2012: Peter Levine, general partner at GitHub's investor Andreessen Horowitz, stated that GitHub had been growing revenue at 300% annually since 2008 "profitably nearly the entire way".[18]
16 January 2013: GitHub announced it had passed the 3 million users mark and was then hosting more than 5 million repositories.[19]
23 December 2013: GitHub announced it had reached 10 million repositories.[20]
GitHub.com is a start-up business, which in its first years provided enough revenue to be funded solely by its three founders and start taking on employees.[24] In July 2012, four years after the company was founded, Andreessen Horowitz invested $100M in venture capital.[3]


#Github demo
* Social coding
* Collaboration
* Web service integration
* Web hosting -- [Github Pages](https://pages.github.com/)


#![bitbucket site logo](http://upload.wikimedia.org/wikipedia/en/f/fc/Bitbucket_Logo.png)
##Integrate with other Atlassian apps
* JIRA
* Confluence
* Stash
* Bamboo
* Crucible


#![gerrit logo](http://upload.wikimedia.org/wikipedia/commons/thumb/4/4d/Gerrit_icon.svg/78px-Gerrit_icon.svg.png)
#Gerrit code review
###Developed at Google for Android project
Note:It was developed at Google by Shawn Pearce (founder of JGit) for the development of the Android project.Originally written in Python like Rietveld, it is now written in Java (Java EE Servlet) with SQL since version 2. Gerrit uses Google Web Toolkit to generate front-end JavaScript code from Java source.


#Repo
###Repo is a tool that makes it easier to work with Git in the context of Android. 
Note:Repo is a repository management tool that we built on top of Git. Repo unifies the many Git repositories when necessary, does the uploads to our revision control system, and automates parts of the Android development workflow. Repo is not meant to replace Git, only to make it easier to work with Git in the context of Android. The repo command is an executable Python script that you can put anywhere in your path. In working with the Android source files, you will use Repo for across-network operations. For example, with a single Repo command you can download files from multiple repositories into your local working directory.


#Content management


#Blog
###[JekyII](http://jekyllrb.com/) 
[阮一峰的Github/JekyII中文教程](http://www.ruanyifeng.com/blog/2012/08/blogging_with_jekyll.html)
###[Ghost](https://github.com/tryghost/Ghost)


#Book writing
###[Pro Git](http://git-scm.com/book/)
###[GotGitHub](https://github.com/gotgit/gotgithub)


#Other stuffs
###Personal backup
###JGit(Git Java wrapper) that is the fundamental of Gerrit, EGit and Jenkins's Git plug-in
###...
###Any cool thing inspired by Git?



#Introduction to Git


#Distributed Version Control
![dcvs](https://www.evernote.com/shard/s220/sh/9fec4d5f-b0d4-47aa-90e3-f8a8e26f437b/65e0ab34b21d065b8f465b5f820e0ea0/deep/0/Git-in-action.png)


#Deﬁnitions
* Working tree <br/>A directory in your ﬁlesystem that is associated with a repository, containing ﬁles & sub-directories.
* Repository <br/>A collection of commits & branches, saved in the .git directory.
* Commit <br/>A snapshot of your working tree at a certain point in time, identiﬁed by a revision number.
* HEAD <br/>The name for the commit thats currently checked out in


#Git repository
repository = object database

![repository](https://www.evernote.com/shard/s220/sh/6d0057d7-9a79-464d-b9d0-229c33ace9f8/9c5ea69a118c40213d25a05de7914398/deep/0/Git-in-action.png)

_.git/objects_


#Git Objects
Every **_commit_** consists of objects of three types:
![git objects](https://www.evernote.com/shard/s220/sh/be1a8182-05ea-4162-a34d-8a21ef3be77e/17e6d23b1e0296e2197d53a0bfb25be1/deep/0/Git-internals.png)
Note:To be precise the **tree & blob** are created when you **add/stage** the commit is created when you -> commit


#Git objects example
![objects](https://www.evernote.com/shard/s220/sh/251fde72-325c-477e-9f8b-cc25bfedd7d0/a6aa64d8c37b64f06ee86efd8ed0adbf/deep/0/Git-in-action.png)



#Git in action


#Git remote commands
* git clone
* git remote
* git fetch
* git pull
* git push


#Git remote commands - cont.
![git remote commands](http://image.beekka.com/blog/2014/bg2014061202.jpg)

[further read](http://www.ruanyifeng.com/blog/2014/06/git_remote.html)


#Commits = local
* **git commit** only affects your repository, not the origin or any other remote repository
* **git push** in order to share your commits
* Commits are cheap & fast
* Commit as often as possible!


#The index
* When you edit/add/remove ﬁles, only your working tree changes
* To commit changes, you ﬁrst save them in the index with **git add** or **git rm**
* **git status** shows the current index
* **git commit** commits only the changes saved in the index, and clears the index afterwards


#Branching & Tagging


#Refs
![refs](https://www.evernote.com/shard/s220/sh/2e2a2d6b-c9d8-4840-b3c3-a6fa282f7ac0/1b91957b25c1ef762e1fc8e0ed2d0b08/deep/0/Git-internals.png)


#Context based development
![https://www.evernote.com/shard/s220/sh/735641f6-0004-481b-b0c0-2b471be481af/b5de0c3caa6f8a3b6248d16a74c1b3e5/deep/0/Git-internals.png](https://www.evernote.com/shard/s220/sh/2e2a2d6b-c9d8-4840-b3c3-a6fa282f7ac0/1b91957b25c1ef762e1fc8e0ed2d0b08/deep/0/Git-internals.png)


#Refs - branches
![branches](https://www.evernote.com/shard/s220/sh/121ca354-6b38-4353-be5f-1f15f03475ef/e49579f6006f7f33f00426bbe3838cfc/deep/0/Git-internals.png)


#Refs - change
![refs change](https://www.evernote.com/shard/s220/sh/4437e3e0-5e74-4d7c-886a-b43f63c05046/d3634e4141dc6057e01f8263e1bb8d4f/deep/0/Git-internals.png)


#Deleting branches
![deleting branches](https://www.evernote.com/shard/s220/sh/854c561e-6ca0-45eb-8bd1-bfc47141d5d4/8646260635f71ca3344a06e0acf40930/deep/0/Git-internals.png)


#Tagging
![tagging](https://www.evernote.com/shard/s220/sh/db71b114-49b9-4d90-9ffd-7d10ebc6482d/bca16b8fad23784b2ebe857f9fa80a60/deep/0/Git-internals.png)


#Branching summary
* Branches are cheap.
* Branch = Named commit.
* Per default you always work on the **_master_** branch.
* A branch is local to your repository,create as many or as little as you like.


#Mergeing with Git


#Conflicts and merging
* Merge as many branches as you want at the same time **_git merge branch_a branch_b_**
* Merged branches can also be deleted
* Conflict markers indicates auto-merge problems 
* Show with git status or git mergetool 
* Use editor or mergetool to fix the conflict 
* Stash the resolved conflict on the index 
* Do a commit


#Non/Fast Forward
![merging](https://www.evernote.com/shard/s220/sh/dc8161bb-3aa8-4f42-8dec-f3fbd3ee1ed7/1768b1028cea7002762426cd0ecf4aba/deep/0/Git-internals.png)


#Cherry-pick
* Sometimes you only want to merge specific commits into another branch
* Git allows this cherry picking **_git cherry-pick <commit>_**


#Rebase
* Alternative to git merge
* Simple rebase pushes the branch onto the HEAD
![rebase](https://www.evernote.com/shard/s220/sh/2aca6f89-3e01-40a2-98fe-111b54906796/b0c1717872eb9acb1453528caecd597d/deep/0/Git-in-action.png)


#Other cool stuffs
* submodule
* stashing
* blame
* bisect
* ...



#Further reading
## Open source books
* [Pro Git](http://git-scm.com/book/)
* [Git Internals](https://github.com/pluralsight/git-internals-pdf)

## Online resources
* [Git - Tutorial](http://www.vogella.com/tutorials/Git/article.html)



#Acknowledge


#Git slides in [slideshare.net](http://www.slideshare.net)
* [Introduction to Git](http://www.slideshare.net/lfittl/introduction-to-git-4642204)
* [Git Internals](http://www.slideshare.net/hagzag/git-internals-1)
* [Git in Action](http://www.slideshare.net/alekseikornev1/git-in-action)


#Html presentation framework
* [reveal.js](https://github.com/hakimel/reveal.js)


#Markdown editor
* [MacDown](https://github.com/uranusjr/macdown) 