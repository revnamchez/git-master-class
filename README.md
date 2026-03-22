# Explain Version Control
- Version control is the practice of tracking and managing changes to files over time, ensuring a complete history of a project. Git is the distributed version control system (DVCS) that performs this tracking locally, while GitHub is a web-based platform for hosting Git repositories online, adding collaboration, management, and automation tools.
- Imagine writing a story, you make changes and save. Version Control tracks every SAVE.

  # Difference between Git and Github
  - Git is a local, open-source version control system (VCS), while GitHub is a web-based, cloud-hosted platform for storing and collaborating on Git repositories. Git is the fundamental tool, and GitHub is a service that builds on top of it, providing a graphical interface and additional features for teamwork.
 
  # List 3 other github alternatives
  1. Gitlab
  2. Bitbucket
  3. Gitea
 
  # Explain the difference between git fetch and git pull
  - The main difference is that git fetch only downloads changes from the remote repository to your local machine, while git pull downloads the changes and automatically merges them into your current working branch.

  # Explain in simple terms git rebase and the command for it
  - Git rebase is a command used to integrate changes from one branch into another, resulting in a cleaner, more linear project history than a traditional git merge. It essentially takes your feature branch's commits and "moves" them to the tip of the target branch, replaying them one by one as if you had branched from that latest point all along. The command
  for it is git rebase <target-branch-name>

  # Explain in simple terms git cherry-pick and the command for it
  - In simple terms, git cherry-pick is a command that allows you to select a specific commit from one branch and apply it to another branch. Instead of merging an entire branch (which brings all changes), you "pick" only the "cherry" (the exact change) you want and add it to your current branch..
