# I am learning git.
To commit any file from my local pc there are some spets:
1) add the changes : git add <file_name> when you have to add all the files then use "." as the file name
2) commit the changes: git commit -m "some message"
3) push the file: git push origin main  => upload local repo content into remote repo. Here origin is the remote repo name. Main is the branch name.
# Init command
1)=>It is used to create new git repo. 
2)commad: git init =>  this command create a default repo into git repo.
3)After creating the init file we will create a new repo in github then copy HTTPS link and run the command to set origin: git remote add origin <link of the repo>
4)To verify the repo we use: git remote -v
5)Check Branch: git branch
6)Rename Branch: git branch -M <new_branch_name>
7)set upstream: means if we don't want to write every time origin main so we can use this command => git push -u origin main. By using the -u no need to again write "git push origin main" directly use "git push" it will push the file in the same origin.
# Git Branch
Check Branch name: git branch
Rename Branch: git branch -M <new-branch-name>
To create new branch: git checkout -b <branch-name>
To switch branch: git checkout <branch-name>
Delete any Branch: git branch -d <branch-name> =>If I am in the feature1 branch then I am not able to delete that branch.
