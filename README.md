# json-server

## Installing json-server

*json-server is a node module, and hence can be installed globally by typing the following at the command prompt:

        $ npm install json-server -g

If you are using OSX or Linux, use sudo at the front of the command. This will install json-server that can be started from the command line from any folder on your computer.

## Configuring the Server

*At any convenient location on your computer, create a new folder named json-server, and move to this folder.
*Download the db.json file provided above to this folder.
*Move to this folder in your terminal window, and type the following at the command prompt to start the server:

        $ json-server --watch db.json -d 2000