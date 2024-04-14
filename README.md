For the first task of this project you will need to accomplish the following:

Set up your local dev environment by downloading the necessary files, tools and dependencies.
Fix the broken client datafeed script in the repository by making the required adjustments to it.
Generate a patch file of the changes you made
(optional): Add unit tests in the test script in the repository.
Submit your work

use "git init" command on cmd if "fatal: not a git repository (or any of the parent directories): .git" error occur

To Create Patch File
- git add -A
- git config user.email "<your_email_address>"
- git config user.name "<your_name>"
- git commit -m "Create Patch File"
- git format-patch -1 HEAD
