Answer 1: --global applies the setting to every repository on your computer for your user. Without it, the setting applies only to the current repository, and in a folder that isn’t a repository the command fails.
Answer 2:  ls -a shows the hidden .git folder. It holds the repository’s internal data: history, config, and objects.
Answer 3: There are about 5 files and folders Git is offering to track. I didn’t write, such as .venv/ and its contents or __pycache__/.
Answer 4: .venv/ (and probably __pycache__/) disappeared from the untracked list.
Answer 5: .gitignore should be committed. It’s a config file that belongs to the project, and committing it means anyone who clones the repo ignores the same files.
Answer 6: README.md moved from “Untracked files” to “Changes to be committed”. In the three-places model, it moved from the working directory to the staging area.
Answer 7: [main 5afdec1] Lab work so far.
Answer 8: The first seven characters are the short commit hash. It’s a unique ID for that commit, used to refer to it for things like git show, checking out, or reverting.
Answer 9: The four steps of the loop are edit, check status, stage (git add), and commit (git commit). Your sheet says “four steps”, so use whichever four your session taught. The usual set is edit → status → add → commit.
Answer 10: README.md has a special name and location because GitHub looks for it at the repository root and displays it as the front page, so visitors see what the project is about.
Answer 11: gh auth login stored an authentication token (credential) on your machine, and Git uses it automatically, so it doesn’t ask for a password on each push.
Answer 12: The front page shows the rendered README.md, because GitHub automatically displays the README for a repository.
Answer 13: Pushing doesn’t change my local history. It only copies my commits to GitHub, and the log looks the same (except the branch labels may now show origin/main).
Answer 14: A private repository exists on GitHub but only you and people you’ve invited can see it. A repository that doesn’t exist on GitHub is only on your computer, with no online copy, no backup, and nothing for the TAs to access.
