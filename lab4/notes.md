# Lab 4 — Git & GitHub

Question 1
`--global` means the Git configuration applies to my user account on the computer and is used by default for all my repositories. If I leave it out, the configuration applies only to the current repository.

Question 2
The `.git` directory appeared in `ls -a` but not in the normal `ls` output because it is a hidden directory. It contains Git's repository data, including the information Git uses to track commits, branches, and the history of the repository.

Question 3
Git was offering to track roughly a thousand files and folders. Most of these were inside `.venv/`, which contains automatically generated Python virtual-environment files that I did not write.

Question 4
The files inside `.venv/` disappeared from the `git status` output after creating `.gitignore`. Git is now ignoring the virtual environment files and the other file types listed in `.gitignore`.

Question 5
`.gitignore` should be committed because it contains the rules that tell Git which files to ignore. Committing it ensures that anyone working on the repository uses the same ignore rules.

Question 6
`README.md` moved from **Untracked files** to **Changes to be committed**. In the three-places model, it moved from the working directory into the staging area, meaning Git is now prepared to include it in the next commit.

Question 7
Git created the commit with the message **“Lab work so far”** and identified it with the commit hash `e2871e6`. It reported that **5 files changed, with 102 insertions**.

Question 8
The first seven characters of my commit hash are `e2871e6`. They are a shortened version of the commit's unique identifier, which Git uses to refer to that specific commit.

Question 9
The four steps are edit or create a file, stage the changes with `git add`, commit the staged changes with `git commit`, and repeat the cycle for the next change.
