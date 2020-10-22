# git-checklist
Main Repo (Upstream)

Fork Repo (Fork)

main <- fork

------------------------------------


## Fork:

1. Clone Remote repo on local machine
>> git clone [repo url]

2. Add remote repo url
>> git remote set-url origin [repo url]

3. Add commit
>> git add .
>> git add [filename]
>> git commit -m "Message"

4. Push branch and branch changes to remote
>> git push origin [branch_name]

5. Update local branch/ take main branch changes
>> git pull origin [branch_name]

6. Fetch particular branch locally (branch should be on remote)
>> git fetch [branch_name]

7. Fetch all remote branches locally
>> git fetch --all

8. Create new branch from updated local branch
>> git checkout -b [new branch name]

9. Delete local branch (current branch should not be the same branch)
>> git branch -D [branch name]

10. Cherry pick (copy br_A commit to br_B)
>> git cherry-pick [commit id]

11. Merge remote/locally branch locally
>> git merge [branch name]

12. Revert modified/tracked file (file exist on remote but made changes on local and have to revert changes)
>> git revert --stage [filename]

13. Revert new/Untrack file (new file)
>> git clean -fd 

14. Resolve conflicts scenario
>> git commit (commit local changes)
>> git pull (pull remote changes)
>> resolve conflicts in local branch
>> git add . (add resovled conflict files)
>> git commit
>> git push (push to remote branch)

15. Update last commit
A. 
>> git add [file_name] / git add .
>> git commit --amend
>> git push -f origin [branch name]

16 Switch branch
>> git checkout [branch name]

17. Set(restore) head to specific commit
>> git checkout [commit id]


18. Commit history
>> git log

19. Current branch status
>> git status

20. List All visible branches
>> git branch

21. List all(visible + hidden) local branches
>> git branch -a

22. Current remote url
>> git remote -v

23. Initialize current directory with git
>> git init

24. Adding author name
>> global: git config --global user.name "Nitin Kadam"
>> local: git config user.name "Nitin Kadam"

25. Adding author email
>> global: git config --global user.email "nitin.learning213@gmail.com"
>> local: git config user.email "nitin.learning213@gmail.com"

26. Check file history
>> git blame [filename]










