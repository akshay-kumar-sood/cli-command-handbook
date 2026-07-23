---> How to chnage commit 

Step 1: check commit history
CMD :   git log --online 

Step 2: start INteractive rebase
CMD :   git rebase -i HEAD~2

Head means latest commit and 2 means last 2 commit.

Nano editor open.

STEP 3: change pick to reword

pick means keep commit as it is
reword means commit content but edit message

STEP 4 : save and exit

save : ctrl 0
ENter
exit : ctrl X

Step 5: Edit the message 

change the message

Step 6: Save 

Step 7 : Verify 
CMD : git log --online
