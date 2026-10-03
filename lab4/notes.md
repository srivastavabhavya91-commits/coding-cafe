# Lab 4 Notes

## Answer 1

The --global flag applies the configuration settings for all Git repositories for your user account on the system. If this flag is not used the settings would only apply to the repository you are currently working in.

## Answer 2

The.git directory appeared in ls -a. Not in ls. Inside.git Git stores all configuration files, repository metadata, object databases commit history and branch references.

## Answer 3

Git offers to track all files and folders in your directory, which often includes hundreds or thousands of files. Files under.venv/ or build folders like __pycache__/ are generated dependency files that were not manually written.

## Answer 4

All files and directories listed in.gitignore (such as.venv/ __pycache__/, *.pyc and.DS_Store) disappeared from the files list in git status.

## Answer 5

.gitignore should be committed because it is a project file that needs to be tracked and shared across collaborators so everyone ignores the files.

## Answer 6

README.md moved from " files" to "Changes to be committed". In the three-places model it moved from the Working Directory to the Staging Area (Index).

## Answer 7

Git printed the commit summary, including the hash the commit message and the number of files changed (1 file changed).

## Answer 8

The first seven characters are the short SHA-1 commit hash. They serve as an ID to identify that commit in the repositorys history.

## Answer 9

The four steps of the Git loop are:

1. Edit / modify files in your working directory.
2. Check repository status with git status.
3. Stage changes using git add.
4. Save the snapshot to history using git commit -m "message".

## Answer 10

README.md is a naming convention recognized by repository hosting services like GitHub. It automatically renders as the project landing page to inform viewers what the repository is about.

## Answer 11

gh auth login authenticates your machine via GitHubs OAuth/ helper storing an access token so Git can securely push and pull without prompting for a password each time.

## Answer 12

README.md is displayed on the page of the repository because GitHub automatically renders markdown files named README at the root directory as the overview of the project.

## Answer 13

No running git log --oneline shows the commit history. Pushing uploads your commits, to the server without altering your local history.

## Answer 14

A private repository exists on GitHubs servers. Maintains version history but access is restricted to authorized collaborators. If a repository does not exist all no code or history is stored online anywhere.