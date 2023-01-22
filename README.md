# Deploy React & Nodejs App to AWS EC2 instances
<br>
<p align="center">
    <img width="200" src="https://myoctocat.com/assets/images/base-octocat.svg">
</p>
<br>
##NODE JS FOREVER START
<br>
1. Go to cd /var/www/html/ and clone node js project
2. git clone https://github.com/Yesh-adithya31/nodejsHosting.git
3. cd nodejsHosting
4. remove current node_modules using rm -rf node_modules
5. install it again npm install
6. npm start(Running on port 8080)
7. Stop ctrl + c or cmd + c
8. Install Globally pm2
9. Install globally npm install forever -g
10. Go to your project folder
11. forever start --minUptime 1000 --spinSleepTime 1000 app.js
