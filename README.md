# GitCommands

Create a new git repo with existing code. 

1. Create a local git repo with:
   git init
   
3. Stage the files by typping:
   git add . (or git add :and the filenames of the files you wish to add)
   
4. Commit the changes locally:
   git commit -m "initial commit"
   
5. Now create a remote repo on github and link it with the use of the provided URL:
   git remote add origin <remote_repo_URL>
   
6. Push project from local to external:
   git push -u origin master
