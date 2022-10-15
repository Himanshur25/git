# git

1. created a new branch and switched to that branch 
`git checkout -b main`
2. Created a new file
`touch b.txt`
3. performed git add and commit with commit name. 
 `git add . `
 `git commit -m "Commit message"`
4. Added one more commit using the same command as 3.
5. `git checkout master`
6. To check all the commits
`  git log`
7. merge main commit with master commit
`git merge main`
8. `git log`
9. Created one more commit 
`git add . `
 `git commit -m "Commit message"`
 10. `git checkout master`
`git add . `
 `git commit -m "Commit message"`
11. Added one more commit using the same command used in 10.
12. `git checkout master`
13. To check all the commits
`  git log`
14. merge main commit with master commit
`git merge main`
15. `git log`
16. created a new branch and switched to that branch 
`git checkout -b main1`
17. created a file
`touch c.txt`
18. Added and commited 
18. `git checkout master`
19. Commited again
20. `git checkout main1`
21. `git rebase master`
22. updated text file
23. To restore the changes `git stash`
24. To check the changes made  ` git stash pop `
25. `git stash list`
26. one more commit on a.txt
 `git add . `
 `git commit -m "Commit message"`
 27. `git checkout main`
 28. one more commit on b.txt
  `git add . `
 `git commit -m "Commit message"`
 29. Taking the commit id using `git log`
 30. `git checkout master`
 31. `git cherry-pick commit-id`
 32. `git checkout master`
 33. `git log`
 34. created multiple stash in a single branch(main) using
   `git stash`
 35. to pop up a particular stash 
 `git stash apply stash@{1}`



