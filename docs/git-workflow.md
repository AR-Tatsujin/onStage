Suggested Git Workflow

All incoming code changes should (not enforced) be a on a separate branch, and a pull request (PR) should be opened from that branch against `master` branch.

Sample git commands:

1. checkout `master` branch

    `git checkout master`


2. merge the upstream develop branch

    `git pull origin master`


3. open a new branch

    `git checkout -b <branch_name>`


4. DO THE WORK


5. Stage the files you want

    `git status`

    `git add <file1> <file2>`


6. Commit with a meaningful message

    `git commit -m "turds"`


7. Push to the same branch onto upstream (the branch will be created if not exist)

    `git push origin <branch_name>`


8. Go to github.com and open an PR
