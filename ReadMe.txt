
1. Initialize the repo first
git init

2. Add the files to git and commit them respectively

3. NOTE: to puch a new repo directly to gitHub user needs to first create new repo on github
In this case user has created repo named RepoFromCmd on github

4. Copy the URL from github in SSH format
git@github.com:DanishMalim/RepoFromCmd.git

5. Asign the origin for newly created repo
git remote origin git@github.com:DanishMalim/RepoFromCmd.git

6. Now push repo to remote site
git push -u origin master
