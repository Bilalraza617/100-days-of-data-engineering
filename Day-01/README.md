# Day 01 - Environment Setup & Git Basics

## Challenge

Set up your data engineering workspace and use Git to create and publish your first challenge repository.

## Learning goals

- Install and verify Python, Git, and a code editor (VS Code or Cursor).
- Create a GitHub repository and connect it to your local machine.
- Practice the basic Git workflow: `clone`, `add`, `commit`, `push`, and `branch`.
- Practice basic terminal navigation and file commands.

## Tasks

### 1. Check your tools

- [ ] Install Python, Git, and VS Code or Cursor if they are not already installed.
- [ ] Open a terminal and verify the installations:

```bash
python --version
git --version
```

If `python` is not recognized on Windows, try `py --version`. Use Git Bash or WSL for the Linux-style commands below.

### 2. Create and clone your challenge repository

- [ ] Create a public GitHub repository named `100-days-data-engineering`.
- [ ] Clone it to your computer:

```bash
git clone https://github.com/Bilalraza617/100-days-of-data-engineering/tree/main
cd 100-days-data-engineering
```

- [ ] Copy this challenge's root `README.md` and `Day-01` folder into the cloned repository.

### 3. Practice terminal basics

From the repository folder, run these commands and confirm what each one does:

```bash
pwd
ls
mkdir terminal-practice
cd terminal-practice
echo "Day 1 Git and terminal practice" > notes.txt
cat notes.txt
grep "terminal" notes.txt
cd ..
```

On Windows Command Prompt, the equivalent commands differ. Git Bash or WSL is recommended for this exercise.

### 4. Practice the Git workflow

- [ ] Check the working tree with `git status`.
- [ ] Create a branch for your work:

```bash
git switch -c day-01-setup
```

- [ ] Add a short introduction and the output of `python --version` and `git --version` to `terminal-practice/notes.txt`.
- [ ] Stage and commit your changes:

```bash
git add terminal-practice/notes.txt
git commit -m "Complete day 1 setup and Git practice"
```

- [ ] Push the branch to GitHub:

```bash
git push -u origin day-01-setup
```

- [ ] Open a pull request on GitHub, review the changed file, and merge it into the default branch.

## Completion checklist

- [ ] Python, Git, and a code editor are installed and verified.
- [ ] The challenge repository is cloned locally.
- [ ] Terminal commands were run and their purpose is understood.
- [ ] A branch was created and pushed.
- [ ] A commit and pull request are visible on GitHub.

## Submission

Add your notes and command outputs to `terminal-practice/notes.txt`. Do not include passwords, access tokens, or other secrets in the repository.
