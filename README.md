Exercise 1.1
git status shows uncommitted files. .gitignore keeps temporary files from being committed. obj folder in this case
git remote add origin connects local repo to remote repo on github acc (?)
git push does a "check in" from local repo to the remote repo (?)
added hash in GitViz under head -> master
after push to origin, both point to same hash

Exercise 1.2
Remote is an alias of the url it is being pointed to
-u means upstream. links repo to the "main" one
Should the readme not be in <h1>? Looks like mine is broken
Connection between local repo name and remote? no idea
remove remote by git remove remote
Looks the same to me compared to method 1

Exercise 1.3
git status deleted when delete command used
c2 delete is staged which is a benefit in it being one less step to do (?)
numbers always increases
bin and obj files ignored

Exercise 2.1
Name of the branch = Head -> master
I did not explicitly name it
Commits total size 179B
Trees total size 33B
Blobs total size 10B
Two processing references instead of 1
Head -> master is now head -> experiment
C2 and C3 added under Head -> experiment
git switch master only to master. git switch - toggles between branches(?)
Head -> moved to master, thus it is now pointing workspace (?) to master
It should contain all changes
By using tag for a release, if a hotfix would be needed you could then branch out from the tagged commit
I could not find procedures for branches overview
Branches and tags are pointers to commits, however a tag is a form of timestamp as to "what has been done up till now"
Dimmed commits, probably commits that are non accessible? Unparented perhaps?
git remote -v
3 worked, Task1, Task-1 and Task_1
task1 marked as HEAD only
Branch pointers and tag all point towards the same except Task1 that points towards latest commit
git switch --detach HereIAm
it points to the commit that the tag points to, but does not  create branch
HEAD points towards a new commit, and HEAD being the only one pointing to it
Warning: you are leaving 1 commit behind, not connected to
any of your branches:

  b96256b Added detached.md

If you want to keep it by creating a new branch, this may be a good time
to do so with:

 git branch <new-branch-name> b96256b

Switched to branch 'task1'
git checkout also creates branch (?)
delete tag git tag --delete <nameoftag>
Do 9  did not work for me

Exercise 2.2
It just merged. Is there supposed to be a special merge??

Exercise 2.3
Only got one branch
^fixed. did not name alias origin, named 2.3 thus causing confusion 

Exercise 2.4
refs/stash added pointing.
head pointing on master, a clean slate 
Worked as expected
new branch st1 pointing to same as master
going from master, modifying a file and then stashing a second time and creating a branch for it created a branch pointing to same as master but st1 pointing at a commit above