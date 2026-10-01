# Lab 4 — Git & GitHub

##Question 1
`--global` means the Git configuration applies to my user account on the computer and is used by default for all my repositories. If I leave it out, the configuration applies only to the current repository.

##Question 2
The `.git` directory appeared in `ls -a` but not in the normal `ls` output because it is a hidden directory. It contains Git's repository data, including the information Git uses to track commits, branches, and the history of the repository.

##Question 3
Git was offering to track roughly a thousand files and folders. Most of these were inside `.venv/`, which contains automatically generated Python virtual-environment files that I did not write.

##Question 4
The files inside `.venv/` disappeared from the `git status` output after creating `.gitignore`. Git is now ignoring the virtual environment files and the other file types listed in `.gitignore`.

##Question 5
`.gitignore` should be committed because it contains the rules that tell Git which files to ignore. Committing it ensures that anyone working on the repository uses the same ignore rules.

##Question 6
`README.md` moved from **Untracked files** to **Changes to be committed**. In the three-places model, it moved from the working directory into the staging area, meaning Git is now prepared to include it in the next commit.

##Question 7
Git created the commit with the message **“Lab work so far”** and identified it with the commit hash `e2871e6`. It reported that **5 files changed, with 102 insertions**.

##Question 8
The first seven characters of my commit hash are `e2871e6`. They are a shortened version of the commit's unique identifier, which Git uses to refer to that specific commit.

##Question 9
The four steps are edit or create a file, stage the changes with `git add`, commit the staged changes with `git commit`, and repeat the cycle for the next change.

## Question 10
`README.md` has a special name and is placed in the root of the repository because GitHub automatically displays it as the main introduction to the project. It gives visitors a quick overview of the project and its contents without them having to open another file.

## Question 11
`gh auth login` authenticated GitHub CLI with my GitHub account and saved the authentication credentials. This allows Git operations such as pushing to GitHub without asking me for my GitHub password each time.

## Question 12
The `README.md` file is shown on the repository's front page and is rendered as formatted text. GitHub automatically displays the root `README.md` as the introduction to the repository.

## Question 13
No, pushing did not change my local commit history. `git push` copies the existing commits from my local repository to GitHub; it does not create a new commit.

## Question 14
A private repository exists on GitHub but is only accessible to people who have been given permission, such as collaborators. If a repository does not exist on GitHub at all, there is no online repository or GitHub location for anyone to access.
