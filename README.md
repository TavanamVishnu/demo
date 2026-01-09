# demo
practicing git
----------------
i am simply editing readme file to check status command<br>
status of files in Git<br>
-----------------------<br>
Untracked-U -> git is not tracking this file<br>
modified-M -> git is tracking but there are some modifications done to this file<br>
staged -> whenever we add files that are modified but not commited they are in staged state ready to commit<br>
unmodified -> unchanged after commited<br>
branches are used to copy status of main branch at a point and work from that state if any eroors <br>occured then they will be still on that branch it doesnt effect main branch<br>
Commands<br>
---------<br>
git add -> adds new or modified files in our working directory to git staging area(ready to commit)(engagement)<br>
git add . -> to take all modifications in working area to staging area<br>
git commit -> (married) but simply commiting doesnt make changes to github<br>
git push -> update repo in github(update local changes to github repo)<br>
git push origin main -> origin means the repo which we cloned and main is the branch <br>
git init -> used to create new git repo<br>
git remote add origin link->add remote repository named origin and give link to the desired repo<br>
git remote -v -> what is remote repo we are using<br>
git branch -> to check which branch we are on<br>
git branch -M main -> to change branch name <br>
git push -u origin main -> -u is used to set upstream like if we are working on smae repo for long time then we dont need to write repeatedly git push origin main from next time we can simply write git push<br>
git checkout -b branchname -> to create new branch and switch to that branch<br>
git checkout branchname -> used to switch between different branches<br>
git branch -d branchname -> to delete a particular branch <br> but cant delete branch we are currently working on<br>
git diff branchname -> used to compare differences between branchname and the branch we are on<br>
pull request (PR) -> let the others know about changes you made to code in your feature branch and wanting to merge with main branch<br>
first PR is reviewed and commented and merged<br>
