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
## $$$ when i chage my git hub project into bitbucket
#useful when setup new repo in bitbucket and already git init folder in pc it's chage to new repo on bitbucket 
git remote set-url origin git://new.url.here
# File deleted than recover it  
git checkout {README.md}
 ```
 
### :smile: EMOJI CHEAT SHEET
[Click Here For EMOJI CHEAT SHEET](http://www.webpagefx.com/tools/emoji-cheat-sheet/)
