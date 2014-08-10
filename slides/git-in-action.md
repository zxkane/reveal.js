##Git in action
![logo](http://rlv.zcache.com/id_fork_that_black_tshirts-r621f1b1216034a3eb8b9eb060cbb6ded_8nax2_512.jpg)


##Git remote commands
* git clone
* git remote
* git fetch
* git pull
* git push


##Git remote commands - cont.
![git remote commands](http://image.beekka.com/blog/2014/bg2014061202.jpg)

[further read](http://www.ruanyifeng.com/blog/2014/06/git_remote.html)


##Commits = local
* **git commit** only affects your repository, not the origin or any other remote repository
* **git push** in order to share your commits
* Commits are cheap & fast
* Commit as often as possible!


##The index
* When you edit/add/remove ﬁles, only your working tree changes
* To commit changes, you ﬁrst save them in the index with **git add** or **git rm**
* **git status** shows the current index
* **git commit** commits only the changes saved in the index, and clears the index afterwards


##Branching & Tagging


##Refs
![refs](https://www.evernote.com/shard/s220/sh/2e2a2d6b-c9d8-4840-b3c3-a6fa282f7ac0/1b91957b25c1ef762e1fc8e0ed2d0b08/deep/0/Git-internals.png)


##Context based development
![https://www.evernote.com/shard/s220/sh/735641f6-0004-481b-b0c0-2b471be481af/b5de0c3caa6f8a3b6248d16a74c1b3e5/deep/0/Git-internals.png](https://www.evernote.com/shard/s220/sh/2e2a2d6b-c9d8-4840-b3c3-a6fa282f7ac0/1b91957b25c1ef762e1fc8e0ed2d0b08/deep/0/Git-internals.png)


##Refs - branches
![branches](https://www.evernote.com/shard/s220/sh/121ca354-6b38-4353-be5f-1f15f03475ef/e49579f6006f7f33f00426bbe3838cfc/deep/0/Git-internals.png)


##Refs - change
![refs change](https://www.evernote.com/shard/s220/sh/4437e3e0-5e74-4d7c-886a-b43f63c05046/d3634e4141dc6057e01f8263e1bb8d4f/deep/0/Git-internals.png)


##Deleting branches
![deleting branches](https://www.evernote.com/shard/s220/sh/854c561e-6ca0-45eb-8bd1-bfc47141d5d4/8646260635f71ca3344a06e0acf40930/deep/0/Git-internals.png)


##Tagging
![tagging](https://www.evernote.com/shard/s220/sh/db71b114-49b9-4d90-9ffd-7d10ebc6482d/bca16b8fad23784b2ebe857f9fa80a60/deep/0/Git-internals.png)


##Branching summary
* Branches are cheap.
* Branch = Named commit.
* Per default you always work on the **_master_** branch.
* A branch is local to your repository,create as many or as little as you like.


##Merging with Git


##Conflicts and merging
* Merge as many branches as you want at the same time **_git merge branch_a branch_b_**
* Merged branches can also be deleted
* Conflict markers indicates auto-merge problems 
* Show with git status or git mergetool 
* Use editor or mergetool to fix the conflict 
* Stash the resolved conflict on the index 
* Do a commit


##Non/Fast Forward
![merging](https://www.evernote.com/shard/s220/sh/dc8161bb-3aa8-4f42-8dec-f3fbd3ee1ed7/1768b1028cea7002762426cd0ecf4aba/deep/0/Git-internals.png)


##Cherry-pick
* Sometimes you only want to merge specific commits into another branch
* Git allows this cherry picking **_git cherry-pick <commit>_**


##Rebase
* Alternative to git merge
* Simple rebase pushes the branch onto the HEAD
![rebase](https://www.evernote.com/shard/s220/sh/2aca6f89-3e01-40a2-98fe-111b54906796/b0c1717872eb9acb1453528caecd597d/deep/0/Git-in-action.png)


##Other cool stuffs
* submodule
* stashing
* blame
* bisect
* ...
