# COMP348Fall2020
#
#
#
 So to start your git journey, if you're on windows you want to install GitBash
 Once that's set up, open it up and cd to the folder in which you want the project to be in
 in bash, run "git clone (url of the git)"
 if done good, there should be a (master) in blue beside the pathname

 then, create a branch
 branches are versions of the master code which you can freely modify without fucking up the whole project
 you can then merge the branch into the master branch when your current child branch is good and working
 to make a new branch, run "git checkout -b (branch name)"
 branch name should either be your name or whatever feature you are currently working on



 when you're done working for the day BUT DON'T WANT TO PUT YOUR CHANGES IN THE MASTER BRANCH,
 you use "git commit -a"
 this will pop up a text file, telling you to add a commit message and warn you of files that were changed
 and files that might not properly be reflected (often subfolders)
 if some folders arent being added properly, run "git add (folder path)"
 otherwise, if you're happy with your commit, enter a commit message in your text editor and save and close it
 comitting means committing to your local files, so theres no danger in comitting as much as you want
 after you've comitted, you want to push it to your branch using "git push"
 this uploads your files to the branch on the internet
 you need to do this before you merge to master


 once you are ABSOLUTELY CERTAIN your work is all good and done, you can merge to master
 you do this by "git checkout master" (this switches you to the master branch)
 then run "git merge (branch name)"
 this is permanent, and can fuck up a lot of shit if you're bad so be careful!
 it isnt irreversible though, but it's a hassle so don't be dumb
