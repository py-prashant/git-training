# GIT Advanced Training Outline

**Target Audience: Software Engineers / CAD Engineers & IT Professionals using Git on a daily basis**

## Duration: 2 Days

### Day 1: Advanced Git Concepts and Internals

#### **Session 1: Review of Git Basics**
- **Topics:**
  - Review of git workflow and frequently used commands
  - Quick review of fundamental concepts: commits, branches, merges, HEAD.
- **Lab Exercises:**
  - Merge conflicts resolution.
  - Rebase a feature branch onto the main branch.

#### **Session 2: Branching Strategies and Workflows**
- **Topics:**
  - Advanced branching models (Git Flow, Forking Workflow).
  - Managing release branches, hotfixes, and feature branches.
- **Lab Exercises:**
  - Simulate a Git Flow: create feature branches, release, and apply a hotfix.
  - Create and apply patches

#### **Session 3: Interactive Rebase and Reflog**
- **Topics:**
  - Using `git rebase` for complex history manipulation.
  - `git reflog` to recover lost commits.
- **Lab Exercises:**
  - Interactive rebase: squash commits, edit commit messages, drop commits.
  - Use `git reflog` to find and restore deleted commits.

#### **Session 4: Advanced Stashing and Cherry-picking**
- **Topics:**
  - Effective use of `git stash` in multi-branch workflows.
  - `git cherry-pick` for managing commits across branches.
- **Lab Exercises:**
  - Manage changes with stashing when switching contexts.
  - Cherry-pick commits from development to release branch.

### Day 2: Automation, Customization, and Troubleshooting

#### **Session 5: Advanced Git Configurations**
- **Topics:**
  - Git configuration levels: system, user, local.
  - Customizing Git with aliases and global settings.
- **Lab Exercises:**
  - Configure aliases for simplifying common tasks.
  - Set up a global ignore file for undesired files.

#### **Session 6: Git Hooks and Automation (Option 1)** 
- **Topics:**
  - Introduction to Git hooks for automating workflows.
  - Writing custom scripts for hooks (pre-commit, post-commit, pre-push).
- **Lab Exercises:**
  - Create a pre-commit hook that runs a linter.
  - Setup a post-commit hook for automated backup of commits.

#### **Session 6: Git Repo (Option 2)** 
- **Topics:**
  - Introduction to the Git Repo tool for managing multiple repositories.
  - Best practices and common commands for Repo.
- **Lab Exercises:**
  - Set up a series of interconnected repositories using Repo.
  - Simulate a multi-repository development scenario and use Repo to synchronize changes.


#### **Session 7: Submodules and Subtrees**
- **Topics:**
  - Managing projects with submodules and subtrees.
  - Dependency management best practices with Git.
- **Lab Exercises:**
  - Add and update a submodule.
  - Merge and update a subtree.

#### **Session 8: Troubleshooting and Recovering**
- **Topics:**
  - Advanced troubleshooting in Git.
  - Recovering from repository issues (corruption, common errors).
- **Lab Exercises:**
  - Simulate and resolve repository issues (detached HEAD, merge conflicts).
  - Perform repository maintenance (prune branches, compress size).

### Additional Features
- **Q&A Sessions:** Daily sessions for doubts and experience sharing.
- **Collaboration:** Pair up participants for lab exercises.
- **Real-world Scenarios:** Discussion of real-world problems faced by participants.