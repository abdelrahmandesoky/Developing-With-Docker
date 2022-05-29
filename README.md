## demo app - developing with Docker

This demo app shows a simple user profile app set up using 
- index.html with pure js and css styles
- nodejs backend with express module
- mongodb for data storage


#### To start the application

1: start mongodb and mongo-express

$ docker-compose -f docker-compose.yaml up
    
## to access the mongo-express on localhost:8080 from your browser_
    
2: in mongo-express - create a new database "my-db"

3: in mongo-express - create a new collection "users" in the database "my-db"       
    
## to start node server 

4:
   $ cd app
   $ npm install
   $ node server.js
    
5: to access the nodejs application from browser 

    http://localhost:3000

#### To build a docker image from the application

    docker build -t my-app:1.0 .      ## the dot at end of line it is represent to the current path of Dockerfile   
    

