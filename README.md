# nodejs-helloworld-api-project
Hello world api project in nodejs



1. Become a root user in EC2 server. 
sudo su - root

2. Install GIT Client in EC2 server
sudo yum install git -y

3. Download code from GIT repository to EC2 Server
git clone https://github.com/codeonedigest/nodejs-helloworld-api-project.git

4. Install NVM (node version manager) in EC2 server
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
. ~/.nvm/nvm.sh

5. Install Node server and NPM in EC2 Instance
nvm install --lts

6. Start node server to run node application
node server.js


7. Now open following url in browser to hit api.
 http://<EC2 Server Hostname>:8080/hellow
