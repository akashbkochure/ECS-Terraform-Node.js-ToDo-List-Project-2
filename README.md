# npm-pm2-Node.js-ToDo-List-Project-Steps:


sudo apt update && sudo apt upgrade -y

sudo apt install nodejs

sudo apt install npm

sudo npm install pm2 -g

git clone https://github.com/akashbkochure/Node.js-ToDo-List-Project-Including-npm-pm2-ECS-Terraform-GitHubActions-Jenkinsfile-Docker.git

cd Node.js-ToDo-List-Project-Including-npm-pm2-ECS-Terraform-GitHubActions-Jenkinsfile-Docker

npm install

pm2 start app.js

http://IP:8000

#########################################

pm2 ls

pm2 logs

pm2 restart app

pm2 monit

pm2 show app

pm2 env 0

pm2 logs app --lines 100

##############################################################

npm install pm2@latest -g

pm2 start server.js

pm2 start server.js --name <app_name>

pm2 restart app_name

pm2 reload app_name

pm2 stop app_name

pm2 delete app_name

pm2 [list|ls|status]

pm2 logs

##############################################################

This project includes node.js app with npm as package manager and pm2 as production-level process manager for Node.js with a built-in load balancer and app is deployed on aws ec2 as monolithic architecture. 

For microservices I have used terraform modules to create ECS-fargate infrastructure and write Dockerfile and push docker iamge to dockerhub registry and deploy services using github-actions. And also use jenkins write groovy scripted Jenkinsfile as cicd tool. (also utilised Docker-Compose).





