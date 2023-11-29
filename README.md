Login/SignUp Authorization app project, using Node.js 

For demonstration purposes, please install the node.js package on your device
https://nodejs.org/en/download/current

After installation, we will need a few packages for this project.
First initialize Node with the following command, be sure to do so in your chosen project folder:
npm init

Go through the terminal prompts, doing so will create a package.json file in your project.

use the following commands to install some dependencies that we'll need:
npm i express ejs
npm i --save-dev nodemon dotenv
npm i bcrypt (for password hashing)
npm i passport passport-local express-session express-flash
npm i method-override