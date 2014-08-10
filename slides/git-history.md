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
