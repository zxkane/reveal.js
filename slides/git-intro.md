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
###Backup
###...
###Any cool thing inspired by Git?
