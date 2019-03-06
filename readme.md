gitrebasepractice
---

GitHub: gitrebasepractice
rebasePractice.zip

https://github.com/mikolodziejczyk/gitrebasepractice
Download rebasePractice.zip, this has all the preparation steps.
Unpack it in a local folder. Skip all the preparation steps.

In GitHub gitrebasepractice there're only changes in master.

## Preparation

1. Create feature_1 branch.
2. In master make changes to firstFile.txt
A change in master.
Commit it with the message:
The first change in master
3. In master make changes to firstFile.txt
The second change in master
 and secondFile.txt
A change in master.
Commit it with the message:
The second change in master
4. Remove thirdFile.txt
Commit it with the message:
The third change in master

Verify the branch history.

Now changes in master are ready, switch to feature_1

5. In feature_1 make changes to firstFile.txt
A change in feature_1.
Commit it with the message:
The first change in feature_1
6. In feature_1 make changes to secondFile.txt
A change in feature_1.
Commit it with the message:
The second change in feature_1
7. In feature_1 remove fourthFile.txt and add fifthFile.txt with:
Added in feature_1
Commit it with the message:
The third change in feature_1

Verify the branch history.

## Rebase

Theory
1. How rebasing works?
2. Which unwanted commits can be avoided by rebasing?

Rebasing branch
1. Go to feature_1 branch.
2. Rebase it into the current master.
3. Resolve all conflicts.
How do you resolve conflicts?
4. Go to master and merge feature_1
5. Remove feature_1

## Stash with VSC

Theory
Does stash apply to untracked files?


1. Create feature_2 branch.
2. In master make changes to firstFile.txt
The third change in master.
Commit it with the message:
The fourth change in master

Go to feature_1

Test stash

3. In feature_1 make changes to firstFile.txt
A change in feature_2.

4. Stash changes (all) using Source control panel
Verify what happened.
Look at firstFile.txt
5. Reapply stash.
Verify what happened.
Look at firstFile.txt

Stash and rebase

Scenario: We need to merge changes from the master but our changes aren't yet ready to commit.

6. Stash all changes using GitLens
7. Rebase feature_2 into master
Will be there any conflicts?
8. Reapply the stash
9. Resolve conflicts
10. Stage and unstage changes.
11. Now you can continue working till the commit is to come.


