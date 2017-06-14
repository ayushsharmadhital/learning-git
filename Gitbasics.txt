Git basics
https://www.taniarascia.com/getting-started-with-git/

Basic command line reference

pwd Print Working Directory – shows the exact directory you’re working in.
ls List Directories – lists all the files and folders in your current directory.
cd Change Directory – change to another directory.
mkdir Make Directory – create a new directory.

Basic Git command reference

git config – Configure Git
git init – Initialize Git repository
git status – Check the status of a Git repository
git add – Track files
git commit – Commit tracked files
git push – Upload files
git pull – Download files

cd Intern-Technorio - goto local project folder
git init - initialise git in the folder
git remote add origin https://github.com/you/project - add project master to the location
git status - status  whther file is tracked or not
git add . - Add ALL files to repo (track and will be added when commit)
git commit -am "Initial Commit" //Commit Tracked Files to repo (-a = all, -m = message) (### If you accidentally forget to add a comment and end up in a strange screen where you can no longer enter any commands, press ESC and type :q! followed by ENTER.)
git push origin master //push to git repo at github.com

PUSH to Live Server with SSH

ssh username@ssh.domain.com //login to live server

git pull origin master //doenload files from git to current location




create a new repository on the command line

echo "# learning-git" >> README.md
  git init
  git add README.md
  git commit -m "first commit"
  git remote add origin https://github.com/aalooksth/learning-git.git
  git push -u origin master
  
…or push an existing repository from the command line

git remote add origin https://github.com/aalooksth/learning-git.git
  git push -u origin master