# Core Git Concepts

These core Git concepts need to be understood through online resources:

- **Git**
- **Local vs Remote Repositories**
- **Clone**
- **Commit**
- **Branch**
- **Merge**
- **Pull/Push**

Git can be used through several interfaces:

---

## Available Git Interfaces

### Option 1: Git CLI (Command Line Interface)

**Pros**:
- Works universally as Git's “native language”  
- Provides deep understanding of Git's inner workings

**Cons**:
- There is a learning curve if you are not used to the terminal (not beginner friendly)

---

### Option 2: GitHub Desktop

**Pros**:
- Beginner-friendly, with a simple UI to visualize changes and commits  
- Easy to set up and start pushing/pulling to GitHub

**Cons**:
- May limit understanding of underlying Git commands

---

### Option 3: VS Code's Integrated Git

**Pros**:
- Can see changes, commits, and branches inside the same editor

**Cons**:
- Like GitHub Desktop, may hide Git's deeper mechanics

---

## Our Recommendation

Learn **Git CLI** (at least the minimal commands), to ensure you're not entirely dependent on a GUI. You should know what’s actually happening when you use a GUI. This understanding will make you far more comfortable debugging Git issues in the future.

### Basic Git Commands

```bash
git init          # Initialize a local repository
git clone <url>   # Clone a remote repository
git status        # Check the state of the working directory and staging area
git add           # Stage changes for commit
git commit -m "message"    # Commit changes
git push          # Push local changes to remote
git pull          # Pull changes from remote to local
git checkout -b <branch_name>  # Create and switch to a new branch
git merge <branch_name>        # Merge a branch into the current branch

```
- Mastering these basics is the key to understanding Git, even if we use a GUI later.
- Then use GitHub Desktop or the Git panel in VS Code.
- For quick commits and everyday tasks,the VS Code interface or GitHub Desktop can be more convenient.
- For more advanced operations (conflict resolution in certain edge cases, interactive rebase, or stashes), the CLI might be more transparent.

---

### Some Suggestions for Reference Materials

- [Git, GitHub, & GitHub Desktop for beginners](https://www.youtube.com/watch?v=8Dd7KRpKeaE)
- [How to use Git and Github](https://www.youtube.com/watch?v=HkdAHXoRtos)
- [Official Git Documentation](https://git-scm.com/doc)
