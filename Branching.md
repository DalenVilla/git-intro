## Module 6: Branching

Branches let you work on changes without touching the main codebase until you're ready. Think of `main` as the "official" version of your project — a branch is a safe copy where you can experiment, break things, and fix them without affecting anyone else.

### 1. See your current branches
Run this to list all branches in your repo (the `*` marks the one you're on):

```bash
git branch
```

### 2. Create a new branch
Run this to create a branch for your change:

```bash
git branch my-feature
```

### 3. Switch to the new branch
Run this to move onto that branch:

```bash
git checkout my-feature
```

> **Tip:** You can combine steps 2 and 3 with `git checkout -b my-feature`.

### 4. Confirm you switched
Run this again — the `*` should now be next to `my-feature`:

```bash
git branch
```

### 5. Make and commit a change
Once on your branch, edits, staging, and committing work exactly like before (Modules 2–4). Commits made here only exist on `my-feature` until merged.

### 6. Switch back to main
Run this to return to the main branch:

```bash
git checkout main
```

Notice your change from `my-feature` isn't visible here — it's isolated on its own branch until you merge it.

### 7. Merge your branch into main
Run this (while on `main`) to bring your changes in:

```bash
git merge my-feature
```

### 8. Push the updated main
Run this to send the merged changes to GitHub:

```bash
git push
```