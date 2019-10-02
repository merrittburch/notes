Helpful git tips

##### Date: 2019-08-13
- make branches on Bitbucket/Github for different projects, merge back to main if it becomes part of main project, or else keep working on branches and switch between them
- Steps for creating a branch and adding it to your computer
```shell
git pull
git checkout name_of_new_branch_created_online
git status # tells you what branch you're on
git add name_of_script_thats_new -m
git commit
git push # no need to specify branch
# Online: merge named pull request, branch to master (step to get code review)
```