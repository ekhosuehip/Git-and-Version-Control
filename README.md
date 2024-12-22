# Git-and-Version-Control

## What is Version Control?
Version control is a tool that tracks changes in code, helps developers work together, and allows you to go back to an earlier version if needed.

---

## Git Vs Github
### **Git**
- Git is a distributed version control system.
- Git is a tool that tracks changes in your code and works on your local machine.

### **GitHub**
- GitHub is a hosting platform for Git repositories.
- GitHub has tools to help teams work together, like pull requests, issue tracking, and hosting websites.

---

## GitHub Alternatives
1. **GitLab**
2. **Azure Repos**
3. **AWS CodeCommit**

---

## Git Fetch vs Git Pull
- **Git Fetch**: Checks for updates in the remote repository but doesn’t change your local files.
- **Git Pull**: Gets the updates from the remote repository and applies them to your local files.

---

## Git Rebase
Git rebase is a way to move your changes to the top of another branch, making the commit history cleaner. It’s like rearranging your work to fit better.

**Command**:
git rebase <branch>

---

## Git Cherry-Pick
Git cherry-pick lets you copy specific commits from one branch to another without merging the whole branch. It’s helpful when you only want certain changes or fixes, not everything from the branch.

**Command**:
git cherry-pick <commit-hash>