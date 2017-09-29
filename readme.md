Desain antar makanan : https://docs.google.com/document/d/1_n81tqQLVJejSEcd7Yyw3WPwSIFadyTuYfiFanViaWg/edit

This is an example of RESTful CRUD in Node.js n mySQL.

## Installation
*for newbies : Clone or download zip to your machine then hit this :

    cd to directory rest-crud

then

    npm install for install all node package dependencies

## Configuration (database)
server.js

        host: 'localhost',
        user: 'root',
        password : 'root',
        port : 3306, //port mysql
        database:'test'



You're gonna need to create a DB named 'test' or whatever you name it,  import t_user.sql


## Open your Browser
And type: localhost:3000/api/user
