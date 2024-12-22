# Task-2-

# Task-2-

Basic Version Control

What is Version Control?
Version control is a system that helps track changes to files over time. It enables teams to collaborate on projects by managing and recording modifications. This allows you to:

Track and revert changes if needed.
Work simultaneously with others without overwriting each other’s work.
Maintain a history of changes for auditing or understanding code evolution.

==============

Difference Between Git and GitHub
Git:
A distributed version control system. It runs locally on your machine to track changes in your project files. Key features include branching, merging, and history tracking.

GitHub:
A web-based platform that hosts Git repositories. It provides collaboration tools, issue tracking, and integration with CI/CD pipelines. GitHub is like a remote storage space for your Git repositories, with additional features for teamwork.

=======

Three GitHub Alternatives

GitLab: A feature-rich platform offering Git repository hosting and DevOps tools, including CI/CD integration and issue tracking.

Bitbucket: A repository hosting service by Atlassian with strong integration into Jira and support for Mercurial (in addition to Git).

SourceForge: One of the original open-source project platforms, offering repository hosting and project management features.

======

Difference Between git fetch and git pull
git fetch:
Retrieves changes from the remote repository but does not merge them into your local branch. It's like checking for updates.

git pull:
Fetches changes from the remote repository and merges them into your current branch. It's a combination of git fetch and git merge.

=======

Git Rebase
Rebasing rewrites the commit history by integrating changes from one branch into another as if they were made sequentially. This makes the history linear and cleaner.

Command:
bash
Copy code
git rebase <branch_name>
For example, to rebase your branch onto main:

bash
Copy code
git checkout your-branch
git rebase main

======

Git Cherry-pick
Cherry-picking applies a specific commit from one branch to another. It's like picking one cherry (commit) from a tree (branch) and moving it to another tree.

Command:
bash
Copy code
git cherry-pick <commit_hash>
For example, to apply a specific commit to your current branch:

bash
Copy code
git cherry-pick abc123
Here, abc123 is the hash of the commit you want to apply.

Let me know if you'd like a deeper dive into any of these concepts!
