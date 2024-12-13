# Blog-Application

1.User Registration (email support)
2.Login/Logout
3.View and Edit Profile
4.Add Blog/Post
5.View Blog/Post
6.Add Comment on a Blog/Post
7.View Comment on a Blog/Post
8.Account Locking (to prevent brute-force attacks by enforcing a maximum number of failed login attempts)

#Technology Used
Node.js (Server side JS)
Express.js (Web Application Framework)
Mongoose.js (ODM - Object Document Mapper)
MongoDB (Document Database)
NodeMailer.js (Email)
Passport.js (Authentication and Session Management)
Passport-local.js (Local Authentication)
Handlebars.js (Template Engine)
Bootstrap.js (Frontend, UI)
Bootstrap-validator.js (HTML Form validation)

#Prerequisites
Insatll Node.js See this for installation steps.
Install MongoDB See this for installation steps.

#Installation
Go to the root dir (Blog-Application).
Use the standard node app installation process to use the application (npm install).
This should install all the dependent node-modules from package.json.

#Start
Usual Mode start (code changes do not reflect on the fly) node app.js
Development Mode Start (code changes reflect on the fly) SET DEBUG=Blog-Post:* & npm run devstart
Open the application in any browser with http://localhost:8080/
