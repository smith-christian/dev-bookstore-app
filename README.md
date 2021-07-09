# Install node in order to run this command lines

# This npm init command will get JSON package ready

`npm init`

#### or

`npm init -y`

# Some basic dependencies for server to be up and runing

#### (ejx is for templating engine and layouts which allowes to layout all the HTML files)

`npm i express ejs express-ejs-layouts`

#### (nodemon will refresh and restart the server when changes made)

`npm i --save-dev nodemon`

#### (mongoose will allow to integrate mongodb)

`npm i mongoose`

#### (To load an enviromet varable to the application download dotenv library using comand below)

`npm i --save-dev dotenv`

#### (install body parer to acces the variable from actual server, but you no longer need to bodyParser as its built into express now)

`npm i body-parser`
