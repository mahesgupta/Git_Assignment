# Git_Assignment
This is my Git assignment

Feature_1
step 4: Commiting this change from Feature_1 branch.
Feature_2
third step: Commiting this change to the Feature_2 branch 

third step another change
Step 6: commiting this change to feature 1 branch
step 7: commiting this change to HotFix branch




# Assignment Description:

* First , I created a directory  __Git_assignment__ and them initiated a git repository inside this directory using "git init ." command.
* Currently we were in the main branch . Now we created two other branches  __Integration__ and __HotFix__  using "git checkout -b \<branch_name> ".
* Now we switched to branch  Integration using "git checkout \<branch_name> ".
* After swithcing the branch into Integration , we created two  sub branches named __Feature_1__ and __Feature_2__ using command "git checkout -b <branch_name> ".
*  We created remote repository on github.com with a with a __README.md__ file .
* Set both the __main__ branch of local repository and __origin/main__ branch of the remote repository to track each other, where __origin__ is the
reference for the remote repository.

* Pushed __Integration__, __HotFix__ , __Feature_1__ and __Feature_2__ branch on the remote repository and set them  up with __origin/Integration__,
__origin/HotFix__ , __origin/Feature_1__ and __origin/Feature_2__ branches to track the corresponding branch.

* Pulled all the changes from remote repository to the local repository to bring down the __README.md__ file.
* Switched to __Feature_2__. branch on the local side and made some changes to the __README.md__ file.
* Pushed the changes made in local __Feature_2__ branches to the __origin/Feature_2__ branch.
* Creadted pull request for the changes in __origin/Feature_2 branch to be reviewed by two reviewers Ratinder and Karan , and be merged into __origin/Integration__ branch.

* Deleted the __Feature_2__ branch locally and pushed this deletion to the remote reposioty for removing its stale reference __origin/Fearture_2 using 
"git push origin :/<branch_name>" .

* Switched to the __Feature_2 branch locally and made some changes in the README.md file and rebsed it to  thr local __Integration__branch , resolved
merge conflict using __P4merge__ mergetool , commited those changes to the __README.md__ file and used command "git rebase --continue" to mave forward
with rebase successfully.
* Creadted two different pull request remotely for __origin/Integraion__ to be reviewed by two reviewer and be meged into the __origin/HotFix__
and the __origin/main__ branches.
* Switched to the Feature_1 on the local side and made some chnages to the __REMOTE.md__ file.
* Pushed the changes in local __Feature_1 branch to the __origin/Feature_1 branch.
* Created three different pull request for the changes in __origin/Feature_1__ branchto be reviewed by two reviewers Ratinder and Karan , and be merged into __origin/Integration__ , origin/HotFix__ ,__origin/main branches.
* Dleted the __Feature_1__ branch locally and pushed this deletion to the remote repository for reviewing its stale reference __origin/Feature__  using 
"git push origin :/<branch_name>"
* Switched to the __HtoFix__ branch on the local and made some changes to the __README.md__ file.
* Pushed the changes made in local __HtoFfix__ branch to the __origin/main__ branch.
* Created two different pull requests for the changes in __origin/HotFix__ branch to be reviewed by two reviewers Ratinder and Karan , and be merged into 
__origin/main__ and __origin/Integration__ branches.

* __NOTE__:  __main__ branch on the local side and __origin/HotFix__ branch on the remote side refer to the __Production__ and __origin/Production__ on the
             local and remote repository respectively.

__Screenshot__:

<img width="680" alt="Screenshot 2023-01-26 at 11 27 10 AM" src="https://user-images.githubusercontent.com/122514232/214768304-b70098f4-81b1-4ce5-92e1-844171a955b5.png">
