# New Setup & Note's Files
Important Setting and Note When Starting New Environments.! 

### :whale: Docker Basic Commands
Using SUDO If Linux 

```ruby
# View running containers
docker ps -a {s q f n f}
# Stop running containers __linux__ -- ALL  Stop 4 Stop RM 4 Remove
docker stop $(docker ps -a -q)  
docker rm $(docker ps -a -q)
# Stop running containers __windows__ -- ALL  Stop 4 Stop RM 4 Remove
docker ps -q -a | xargs docker rm
# Remove  Docker images {$$}
docker rmi -f {IMAGENAME OR CODE}
# View installed  Docker Images
docker images
# Run Images with shell {$$}
docker run -i -t {IMAGENAME} /bin/bash
# Run Images with shell forward with PORT -p 80:80
docker run -i -t -p 80:80 {IMAGENAME} /bin/bash
```
### :octocat: Git Basic Commands 

```ruby
# Git command --help
git clone
git status
# if not added new file   . OR -A  all file 
git add {--help more detail}  
# -m for msg what are we do with file
git commit -m "Add Change Detail"  
# now we are using push for file upload in github
git push 
# download from other pc on github same repo
git pull 

#…or create a new repository on the command line
echo "# laravel_snippet" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/jeeteshnariya/laravel_snippet.git
git push -u origin master

# …or push an existing repository from the command line
git remote add origin https://github.com/jeeteshnariya/laravel_snippet.git
git push -u origin master

#Restore Last Commit and remove all chage's file clean to starting point
#If you want to revert changes made to your working copy, do this:
git checkout .
#If you want to revert changes made to the index (i.e., that you have added), do this. Warning this will reset all of your unpushed commits to master!:
git reset
#If you want to revert a change that you have committed, do this:
git revert <commit 1> <commit 2>
#If you want to remove untracked files (e.g., new files, generated files):
git clean -f
#Or untracked directories (e.g., new or automatically generated directories):
git clean -fd
 ```
### :smile: EMOJI CHEAT SHEET
[Click Here For EMOJI CHEAT SHEET](http://www.webpagefx.com/tools/emoji-cheat-sheet/)
