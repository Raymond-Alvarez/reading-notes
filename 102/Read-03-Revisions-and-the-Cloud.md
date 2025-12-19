# Revisions and the Cloud

### <u>Version Control</u>

**Version Control** is a system that lets you save and revisit different versions of a file or project. A **Version Control System (VCS)** helps you go back to earlier versions, see what changed, who changed it, compare updates, and fix mistakes easily.

---

### <u>Cloning</u>

**Cloning** in Git means making a copy of an existing Git repository from a server. You do this using the **`git clone`** command and the repository’s URL.

When you clone a repo:

- All versions of all files are copied  
- A new directory is created  
- A .git folder is added  
- Git checks out the newest version of the project  

Example command:

- `git clone https://github.com/test`

---

### <u>Commands to track and stage files</u>

The linux command used to track and stage files is **`git add`**.

To stage a single file:  

- `git add "filename"`

To stage all files:  

- `git add .`

---

### <u>Take a snapshot of your changed files</u>

Saving your changes in Git is called a **commit**, and Git creates a snapshot of your project when you commit.

Commit staged changes with a message:

- `git commit -m "any message here"`

Example with details:

- `git commit -m "made change x,y,z"`

Commit all modified tracked files:

- `git commit -a`

---

### <u>Sending changed files to Github</u>

To send your changes to a remote repository, referred to as "pushing changes", use:

- `git push origin master`

This pushes your changes from the local **master** branch to the remote repository named **origin**. When you clone a repo, Git automatically names the original server **origin**.
