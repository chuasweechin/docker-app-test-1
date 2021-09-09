# docker-app-test-1
### Question:
Dockerish the NodeJS app in this repo. Write a Dockerfile from scratch to achieve the goals below:

### Goals are:
1. Create a Docker image using it
2. Run the built Docker image
3. Access server app by: curl http://localhost:7070 and get a valid response

### Requirements to run a NodeJS app:
- Require node:14 image
- Run “npm install package.json” at project root to install dependencies
- Start Node server by running “node server.js” at project root
- Server will require PORT 7070 to be exposed
