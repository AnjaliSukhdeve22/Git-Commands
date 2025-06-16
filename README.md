Great, Pawan! You’ve already seen the **basic Git commands**. Now let’s go deeper into **advanced and useful Git commands**, categorized for easy understanding.

---

## 🚀 All Other Important Git Commands (with Examples)

---

### 🔍 **1. Checking & Inspecting**

| Command                | Purpose                             |
| ---------------------- | ----------------------------------- |
| `git log`              | Show commit history                 |
| `git log --oneline`    | Short commit history                |
| `git log --graph`      | Visual graph of branches            |
| `git show <commit-id>` | Details of a specific commit        |
| `git diff`             | Show what has changed (unstaged)    |
| `git diff --staged`    | Show changes that are staged        |
| `git blame <file>`     | See who changed each line of a file |

---

### 🛠️ **2. Undo, Reset, and Revert**

| Command                  | Purpose                               |
| ------------------------ | ------------------------------------- |
| `git reset <file>`       | Unstage a file                        |
| `git reset --hard`       | Discard all changes (dangerous!)      |
| `git reset <commit>`     | Move HEAD to an old commit            |
| `git checkout -- <file>` | Revert file to last commit            |
| `git revert <commit>`    | Make a new commit that undoes another |

---

### 🌿 **3. Branching**

| Command                | Purpose                                         |
| ---------------------- | ----------------------------------------------- |
| `git branch`           | List branches                                   |
| `git branch <name>`    | Create a new branch                             |
| `git checkout <name>`  | Switch to branch                                |
| `git switch <name>`    | Alternative to `checkout`                       |
| `git merge <branch>`   | Merge another branch into current               |
| `git branch -d <name>` | Delete a branch                                 |
| `git rebase <branch>`  | Move commits to a new base (cleaner than merge) |

---

### ☁️ **4. Remote (GitHub, GitLab, etc.)**

| Command                       | Purpose                                  |
| ----------------------------- | ---------------------------------------- |
| `git remote -v`               | Show remote URLs                         |
| `git remote add origin <url>` | Connect local repo to remote             |
| `git fetch`                   | Get latest changes (but don’t apply yet) |
| `git pull`                    | Get and apply changes                    |
| `git push`                    | Send changes to remote                   |
| `git push -u origin <branch>` | Push and set upstream                    |

---

### 🧹 **5. Stashing (Temporary Save)**

| Command           | Purpose                  |
| ----------------- | ------------------------ |
| `git stash`       | Save uncommitted changes |
| `git stash list`  | See stashes              |
| `git stash apply` | Reapply last stash       |
| `git stash drop`  | Delete stash             |

---

### 🧪 **6. Tags (for releases)**

| Command                      | Purpose            |
| ---------------------------- | ------------------ |
| `git tag`                    | List all tags      |
| `git tag <name>`             | Create tag         |
| `git tag -a <name> -m "msg"` | Annotated tag      |
| `git push origin <tag>`      | Push tag to remote |
| `git push origin --tags`     | Push all tags      |

---

### 🧰 **7. Config and Setup**

| Command                                            | Purpose                  |
| -------------------------------------------------- | ------------------------ |
| `git config --global user.name "Pawan"`            | Set your name            |
| `git config --global user.email "you@example.com"` | Set your email           |
| `git config --list`                                | See current config       |
| `git help <command>`                               | Get help for any command |

---

### 🔁 **8. Cherry Pick (Use Specific Commit)**

| Command                    | Purpose                                     |
| -------------------------- | ------------------------------------------- |
| `git cherry-pick <commit>` | Apply one specific commit to current branch |

---

### 📦 **9. Submodules (Nested Repo)**

| Command                       | Purpose               |
| ----------------------------- | --------------------- |
| `git submodule add <url>`     | Add submodule         |
| `git submodule update --init` | Initialize submodules |

---

## ✅ Bonus: Useful Shortcuts

```bash
git log --oneline --graph --all
# Great for visualizing all branches and commits
```

---

Do you want a **cheat sheet PDF** for all these commands or a **hands-on mini project** to practice Git and GitHub?
