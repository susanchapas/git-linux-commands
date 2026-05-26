# Linux & Git Cheat Sheet

A quick reference for common Linux and Git commands.

## Linux Commands

| Command | Description | Example |
|---------|-------------|---------|
| `pwd` | Print the current working directory | `pwd` |
| `ls` | List directory contents (`-l` long, `-a` all, `-h` human-readable) | `ls -lah` |
| `cd` | Change directory (`..` goes up, `~` goes home) | `cd ~/projects` |
| `mkdir` | Create a new directory (`-p` for nested paths) | `mkdir -p src/utils` |
| `rm` | Remove files or directories (`-r` recursive, `-f` force) | `rm -rf build/` |
| `cp` | Copy files or directories (`-r` recursive) | `cp -r src/ backup/` |
| `mv` | Move or rename files and directories | `mv old.txt new.txt` |
| `cat` | Display contents of a file | `cat readme.md` |



## Git Commands

| Command | Description | Example |
|---------|-------------|---------|
| `git init` | Initialize a new Git repository | `git init` |
| `git clone` | Clone an existing repository | `git clone <url>` |
| `git status` | Show the working tree status | `git status` |
| `git add` | Stage changes for commit (`.` for all) | `git add readme.md` |
| `git commit` | Record staged changes to the repository | `git commit -m "add cheat sheet"` |
| `git push` | Upload local commits to a remote | `git push origin master` |
| `git pull` | Fetch and merge changes from the remote | `git pull origin master` |
| `git branch` | List, create, or delete branches | `git branch feature/login` |
| `git checkout` | Switch branches or restore files | `git checkout feature/login` |
| `git merge` | Merge another branch into the current one | `git merge feature/login` |
| `grep` | Search text using patterns (`-r` recursive, `-i` ignore case) | `grep -ri "TODO" src/` |
| `find` | Search for files and directories | `find . -name "*.js"` |
| `chmod` | Change file permissions | `chmod +x script.sh` |
