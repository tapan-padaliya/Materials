# Backend Using Node Express MongoDB

to Setup Backend you can follow this tutorial if the middleware, packages & Technology i have used. 

Packages : 
    nodemon
    express
    cors
    dotenv
    mongoose

Make Folder Named Backend or Server
open with CMD and give following Commands

[initialization of node]
npm init -y

[install packages and dependency for server]
npm i nodemon express cors dotenv mongoose

{if you are using git then make sure to add .gitignore and add unnecessary files and directory.}

[setup scripts]
(remove old scripts available in package.json and add this new 2 scripts)
"start":"node server.js",
"server":"nodemon server.js"
(suggests to use `npm run server` to avoide restarting node script)

[Create entry file / main file ]