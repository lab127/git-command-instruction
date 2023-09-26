# Git Instruction after Create a Repo

### **Quick setup** — if you’ve done this kind of thing before

[Set up in Desktop](https://desktop.github.com) **or** HTTPS/SSH

Get started by [creating a new file](/lab127/git-command-instruction/new/main) or [uploading an existing file](/lab127/git-command-instruction/upload). We recommend every repository include a [README](/lab127/git-command-instruction/new/main?readme=1), [LICENSE](/lab127/git-command-instruction/new/main?filename=LICENSE.md), and [.gitignore](/lab127/git-command-instruction/new/main?filename=.gitignore).

### …or create a new repository on the command line


```bash
echo "# git-command-instruction" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:lab127/git-command-instruction.git
git push -u origin main
```

### …or push an existing repository from the command line

```bash
git remote add origin git@github.com:lab127/git-command-instruction.git
git branch -M main
git push -u origin main
```

### …or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

[Import code](/lab127/git-command-instruction/import)
