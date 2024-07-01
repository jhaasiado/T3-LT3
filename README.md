#Steps to Connect to GitHub:

1. ##Verify SSH Key: ##
Open the shell terminal in Jojie and execute the following command to verify that your SSH key has been successfully added:
`ssh -T git@github.com` (Assumingly, you already have SSH keys from previous terms. If none, please refer to A-16 of PDS.

3. ##Create a local folder## where you want to store local copies of the git repository.
This can be done via the pane on the left (in Jojie).

4. ##Navigate to Local Folder:## In the shell terminal, navigate to this local folder.
For example: `cd [folder path of the git repository]`

5. ##Initialize and Clone Repository:##   
Run the following Git commands:
`git init`
`git remote add origin 'git@github.com:aim-msds-pt-2025b/T3-LT3.git'`
`git clone 'git@github.com:aim-msds-pt-2025b/T3-LT3.git'`

7. ##Confirm the status ## of your Git repository by running:
`git status`
There should be a folder called `T3-LT3` that would appear in your local folder
git status can be confirmed by running the command `git status`

8. ##Verify Repository Contents:##
Check if the cloned repository contains the same files as seen via an internet browser. Try pushing a change by uploading a test file via the pane on the left in Jojie, committing with matching comments, and pushing the changes.

