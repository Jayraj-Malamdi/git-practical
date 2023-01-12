# git-practical
## Create one repository for practical and provide the link of it for review. 

Repository link:  

https://github.com/Jayraj-Malamdi/git-practical 

pdf file link :
(https://simformsolutionspvtltd-my.sharepoint.com/:b:/g/personal/jayraj_simformsolutions_com/Eeb6tiTRxsdFtulbk-cBKSsBhdLhBuXMQkOoqWm2OjBZSg?e=DFNsF5)

## Work on below points: 

### 1. Pull and Merge difference 
Make example of pull request and two branch merge event. 

- First initiated Git repository. 
- Created m1.html file in master branch and pushed it into git repository. 
- Now created d1.html file in dev branch and pushed it into git repository. 
- Now going back to master branch and run pull command. 
 
 ``` git pull origin ```
 
### 2. Rebase 
Try to rebase feature branch with master branch 

- Now in this, I created a new file, named m2.txt in master branch and pushed it into git   repository. 
- Now I created a new file, named d2.txt in dev branch and pushed it into git repository. 
- now checkout in master branch, and run rebase command. 

``` git rebase branch_name ```

### 3. Change commit message 
Commit push on commit in feature branch and then change commit message 

- To change commit, we need to execute this code: 

```git commit --amend -m "New message" ```

``` git push --force repository-name branch-name ```

### 4. cherry pick 
Pick some commits from feature branch to master branch. 

#### CHERRY PICK :  
* Cherry picking in Git means to choose a commit from one branch and apply it onto another. 
* This is in contrast with other ways such as merge and rebase which normally apply many commits onto another branch. 
### STEPS :
- first created a new file d3.txt in dev branch and pushed it into master branch. 
- NOW I go back into master branch, in which I am merging. And cherry-pick is executed by running these commands: 

``` git cherry-pick super-long-hash-here ```

- And now I pushed this changes into git repository. 

#### 5. Drop commit 
Remove some commit from feature branch. 

- The HEAD~1 means the commit before head. 

 ### STEPS :
- FIRST, I created a new file m4.txt, in master branch and committed it. 
- Since changes have not been pushed, we need to run this code: 

``` git reset --hard HEAD~1 ```

- And if changes are pushed, we need to run this code: 

``` git push origin HEAD --force ```
 

 

 
