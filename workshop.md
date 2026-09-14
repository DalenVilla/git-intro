# Git & GitHub Hands-On Workshop

Welcome! Today you'll learn to track, stage, commit, and push code from the terminal.

---

## Workshop Setup

Go to [github.com/codespaces](https://github.com/codespaces) and click **Blank** (under "Explore templates").

Open your terminal:
* **Shortcut:** `Ctrl + ~` (or `Cmd + ~` on Mac)
* **Menu:** Terminal > New Terminal

---

## Module 1: Forking & Repository State

### 1. Fork the repository
Go to the repo on GitHub and click **Fork** (top right) to create your own copy.

### 2. Clone your fork
Run this to pull your fork down to your machine:

```bash
git clone https://github.com/YOUR-USERNAME/git-intro.git
cd git-intro
```

### 3. Check current status
Run this to see your branch and any modified files:

```bash
git status
```

---

## Module 2: Making a Change

### 1. Open the file
Open `hello.txt` (or similar) in the editor.

### 2. Edit the content
Change "Hello, World!" to say hello with your own name instead.

### 3. Check status again
Run this to see the file marked as modified:

```bash
git status
```

---

## Module 3: Staging

### 1. Stage the file
Run this to add your change to the staging area:

```bash
git add hello.txt
```

### 2. Confirm it's staged
Run this to see the file listed as "changes to be committed":

```bash
git status
```

---

## Module 4: Committing

### 1. Commit the change
Run this to save your staged change with a message:

```bash
git commit -m "Update greeting with my name"
```

### 2. Confirm the commit
Run this to see your commit in the project history:

```bash
git log
```

---

## Module 5: Pushing

### 1. Push to GitHub
Run this to send your commit up to the remote repository:

```bash
git push
```

### 2. Confirm on GitHub
Go to your repo on GitHub and refresh the page to see your change reflected.

---

## Bonus Module: Initializing a Repo
You will do this when you create your own projects.

### 1. Create a new folder
Run this to make a new project folder and move into it:

```bash
mkdir my-project && cd my-project
```

### 2. Initialize git
Run this to turn the folder into a git repository:

```bash
git init
```

### 3. Confirm it worked
Run this to see the new repo's status:

```bash
git status
```

---

