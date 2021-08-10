# twitter-clone
Getting Started
These instructions will get you a copy of the project up and running on your local machine.

Prerequisites
Make sure you have a running MongoDB instance.

Configuration
Create a file in server/.env and update the values 

PORT=3001
MONGO_URI=mongodb+srv://akashgvps:Aa@933570@twitterclone.y8jsw.mongodb.net/twitterclone?retryWrites=true&w=majority
JWT_SECRET=jwt-secret
JWT_EXPIRES=3600

Installing
Install server dependencies

$ cd server
$ npm install
Install client dependencies

$ cd client
$ npm install
Start the server in development mode
$ cd server
$ npm run dev
If everything was successful, you should see the messages being displayed in the terminal, telling that the server has successfully connected to a MongoDB and runs on a given port.

Start the client
$ cd client
$ npm start
Now, the app should be running on http://localhost:3000.
