# gitlab.docker.node
Features Docker and Node.js (can be used for GitLab CI/CD with Docker executor)

## What is it for?
If you want to:
- build an app using node.js
- package and deploy this app via Docker
- Do all this inside a container

you will need an image like this which comes with node and Docker installed.

### Why should I build and package an app INSIDE a container?
If you use GitLab CI/CD, you can build and package your apps directly on a server's system, or use an isolated container. 
This creates a few benefits:
- No dangerous situations for the build sever
- No need to install build tools
- Can be scaled or multiplied in seconds
