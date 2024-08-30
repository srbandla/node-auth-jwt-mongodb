# node-auth-jwt-mongodb
What's inside this repo?
User signup/registration with Email verification.
User Login.
Forgot password and reset password.
Session management using JWT (JSON Web Tokens).
Bonus: Simple Referral System!
For a more detailed explanation of the code, you can refer to my medium post associated with this project. It is split into two parts.

Part I - Build User signup with email verification, forgot password and reset password.

Part II - Integrate JWT and Build a Simple Referral System.

Built With
Node.js - JavaScript runtime built on Chrome's V8 JavaScript engine.
Express.js - Minimal and flexible Node.js web application framework
MongoDB - Cross-platform document-oriented database program
Getting Started
To get a local copy up and running follow these simple steps :

Prerequisites
To run this project, you'll need to have the following installed:

Node.js : https://nodejs.org

npm :

npm install npm@latest -g
MongoDB : https://mongodb.com

You can also use MongoDB Atlas if you prefer.

Installation
Register at SendGrid SendGrid and create an API KEY.

Clone the repo :

git clone https://github.com/PraneshASP/node-authentication-jwt-mongodb.git
Install dependencies (use sudo if required) :

npm install
Create .env file and configure :

MONGO_URI = <MONGODB_URL>
JWT_SECRET = <SOME_LONG_SECURE_SECRET>
SG_APIKEY = <SENDGRID_API_KEY>  //For sending emails
Start the server :

npm start
