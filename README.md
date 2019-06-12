Test-Archive-Branch is created to check whether branch-archiving happens correctly and is there a way to restore the archived+deleted branch.
Steps:
	1. Archive a branch with a tag using the command: git tag archive/<branchname> <branchname>
	2. Now delete the branch using the command: git branch -d <branchname>
Command to restore the branch
git checkout -b <branchname> archive/<branchname>
