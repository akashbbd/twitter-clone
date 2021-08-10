# twitter-clone
Getting Started <br/>
These instructions will get you a copy of the project up and running on your local machine.

<b>Prerequisites</b><br/>
Make sure you have a running MongoDB instance.

<b>Configuration</b><br/>
Create a file in server/.env and update the values <br/>

PORT=3001<br/>
MONGO_URI=mongodb+srv://akashgvps:Aa@933570@twitterclone.y8jsw.mongodb.net/twitterclone?retryWrites=true&w=majority<br/>
JWT_SECRET=jwt-secret<br/>
JWT_EXPIRES=3600<br/>

<b>Installing</b><br/>
Install server dependencies

$ cd server<br/>
$ npm install<br/>
<b>Install client dependencies</b><br/>

$ cd client<br/>
$ npm install<br/>
<b>Start the server in development mode</b><br/>
<br/>$ cd server<br/>
$ npm run dev<br/>
<br/>If everything was successful, you should see the messages being displayed in the terminal, telling that the server has successfully connected to a MongoDB and runs on a given port.<br/>

<b>Start the client</b><br/>
$ cd client<br/>
$ npm start<br/>
Now, the app should be running on http://localhost:3000.<br/>
