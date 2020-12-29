# Git Learning Notes;

Adding notes for myself about Git:


Course: Introduction to Git and Github (Coursera and Google).

WEEK 1:
link: 
https://www.coursera.org/learn/introduction-git-github


Installing Git on Ubuntu: 

sudo apt update; apt install git

link: 
https://git-scm.com/download/linux


Git installation instructions for each platform:

link: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

Acessing the Git Directory:
- ls -la or
- ls -l .git/

3 Project Stages:
- 1: Modified:
  - git init
  - git status
	
- 2: Staged:
  - git add .
	
- 3: Commited: 
  - git commited -m "add comment"

To Check the configuration on the file:
- git config -l

To track the commits:
- git log

To add and commit files automatically:
- git commit -a -m "commment here------"

Produces patch text:
- git log -p	

Shows various objects:
- git show	

Is similar to the Linux `diff` command, and can show the differences in various commits:
- git diff	

Allows a user to interactively review patches to add to the current commit:
- git add -p	

Similar to the Linux `mv` command, this moves a file:
- git mv	

Similar to the Linux `rm` command, this deletes, or removes a file:
- git rm .git	


_ More about Commits:  
- impassioned: https://commit.style/

/* More Information: */

- Linux kernel documentation: https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/Documentation/process/submitting-patches.rst?id=HEAD

- Setting your email in Git: https://docs.github.com/en/free-pro-team@latest/github/setting-up-and-managing-your-github-user-account/setting-your-commit-email-address

- "Keeping your email address private: https://docs.github.com/en/free-pro-team@latest/github/setting-up-and-managing-your-github-user-account/setting-your-commit-email-address
 
 - Advanced Git Cheat Sheet: https://git-scm.com/docs/git-commit#Documentation/git-commit.txt---all

