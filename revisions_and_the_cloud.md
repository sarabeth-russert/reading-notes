## Code 102
#### Day 2

**Revisions and the Cloud**

*Version Control Systems* (now referred to as VCS) allow you to record, track, modify, revert a file or set of files.

*Local VCS* can be used on a database on your hardrive.

*Centralized VCS* created because of the need for more efficient collaboration. Streamlines, allows greater admin control and assignment ability, allows you to see your team members activity.

*Distributed VCS* Same as CVCS but allows your repository to be stored as a mirror in many different locations to prevent loss in the event of a catastrophic crash. 

**About Git**
Git is a DVCS that stores in a system file using snapshots when you commit. Operations are local to your system so you can work offline from your personal computer. Tracked changes are applied with every commit. Git prevents the loss of data through mirrored storage and a defensive system. Git has it's roots in open source Linux Kernel. There was some drama between Kernel and the hosting site and chief Kernel architecht Linus Torvalds broke away and began creating Git. They wanted a non- linear, fast DVCS, capable of supporting large project with a simple design.

**How to set up a git repository from terminal**
- cd `<desired directory>`
- git init
- git add *.c
- git add LICENSE
- git commit -m "your message here"

**Files can be in 3 states with Git locally**

1. Modified - changed but not stored
2. Staged - flagged version to be changed with the next snapshot
3. Commited - data securely stored locally

**Local Repository Structure**
- Working Directory - actual files stored here
- Index - area used for stagging - git add
- Head - most recent commit - git commit

![photo of local repo structure](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)


[Return to the Main Page](README.md)