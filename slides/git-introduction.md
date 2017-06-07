## Introduction to Git
![logo](http://planetozh.com/blog/wp-content/uploads/2012/11/git-t-shirt.png)


## Distributed Version Control
![dcvs](https://www.evernote.com/shard/s220/sh/9fec4d5f-b0d4-47aa-90e3-f8a8e26f437b/65e0ab34b21d065b8f465b5f820e0ea0/deep/0/Git-in-action.png)


## Deﬁnitions
* Working tree <br/>A directory in your ﬁlesystem that is associated with a repository, containing ﬁles & sub-directories.
* Repository <br/>A collection of commits & branches, saved in the .git directory.
* Commit <br/>A snapshot of your working tree at a certain point in time, identiﬁed by a revision number.
* HEAD <br/>The name for the commit thats currently checked out in


## Git repository
repository = object database

![repository](https://www.evernote.com/shard/s220/sh/6d0057d7-9a79-464d-b9d0-229c33ace9f8/9c5ea69a118c40213d25a05de7914398/deep/0/Git-in-action.png)

_.git/objects_


## Git Objects
Every **_commit_** consists of objects of three types:
![git objects](https://www.evernote.com/shard/s220/sh/be1a8182-05ea-4162-a34d-8a21ef3be77e/17e6d23b1e0296e2197d53a0bfb25be1/deep/0/Git-internals.png)
Note:To be precise the **tree & blob** are created when you **add/stage** the commit is created when you -> commit


## Git objects example
![objects](https://www.evernote.com/shard/s220/sh/251fde72-325c-477e-9f8b-cc25bfedd7d0/a6aa64d8c37b64f06ee86efd8ed0adbf/deep/0/Git-in-action.png)

