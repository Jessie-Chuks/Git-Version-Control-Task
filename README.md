# Git/Version Control Task
Learnable week2 task for git and version control
### 1. Explain Version Control

Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later. It enables multiple people to work on a project simultaneously, tracks changes, and facilitates collaboration. Version control is crucial for software development, allowing developers to manage code revisions, track changes, and collaborate seamlessly.

---

### 2. Explain the Difference Between Git and GitHub

**Git:**
Git is a distributed version control system that enables developers to track changes in source code during software development. It allows for collaboration, branching, and merging, and is designed to be fast and efficient.

**GitHub:**
GitHub, on the other hand, is a web-based platform that provides hosting for Git repositories. It adds a user-friendly interface, collaboration features, and additional tools like issue tracking and project management. While Git is the version control system, GitHub is a platform built around it to enhance collaboration and project management.

---

### 3. List 3 Other GitHub Alternatives

- **GitLab:**
   GitLab is a web-based platform that provides Git repository management, continuous integration, and more. It offers features similar to GitHub but can also be self-hosted.

- **Bitbucket:**
   Bitbucket is a Git and Mercurial-based platform that provides source code management and collaboration. It offers free private repositories and integrates with other Atlassian products.

- **SourceForge:**
   SourceForge is an older platform that hosts version control repositories and provides project management tools. It supports both Git and Subversion.

---

### 4. Explain the Difference Between `git fetch` and `git pull`

**Git fetch:**
`git fetch` is a command that downloads changes from a remote repository to your local repository. However, it does not automatically merge those changes into your working directory. It is useful for seeing what changes are available without applying them immediately.

**Git pull:**
`git pull` is a combination of two commands: `git fetch` and `git merge`. It fetches changes from the remote repository and automatically merges them into your current branch. It is a more straightforward way to update your local repository with the changes from the remote.

---

### 5. Explain in Simple Terms `git rebase` and the Command for It

**Git Rebase:**
`git rebase` is a command used to integrate changes from one branch into another by moving or combining a sequence of commits. It is often used to maintain a cleaner, more linear commit history compared to traditional merging.

**Command:**
```
git rebase <branch-name>
```

---

### 6. Explain in Simple Terms `git cherry-pick` and the Command for It

**Git Cherry-Pick:**
`git cherry-pick` is a command that allows you to apply a specific commit from one branch to another. It is handy when you want to pick and choose individual commits and apply them to a different branch.

**Command:**
```bash
git cherry-pick <commit-hash>
