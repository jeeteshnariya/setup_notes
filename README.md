# New Setup & Note's Files
Important Setting and Note When Starting New Environments.! 

### :whale:Docker Basic Commands
Using SUDO If Linux 

 ```ruby
 # View running containers
 docker ps -a {s q f n f}

 # Stop running containers
 docker stop $(docker ps -a -q)
 docker rm $(docker ps -a -q)

 # Remove  Docker images {$$}
 docker rmi -f {IMAGENAME OR CODE}
 
 # View installed  Docker Images
 docker images

 # Run Images with shell {$$}
 docker run -i -t {IMAGENAME} /bin/bash

 # Run Images with shell forward with PORT -p 80:80
 docker run -i -t -p 80:80 {IMAGENAME} /bin/bash

 ```
 

 

