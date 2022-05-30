## demo app - developing with Docker

This demo app shows a simple user profile app set up using 
- index.html with pure js and css styles
- nodejs backend with express module
- mongodb for data storage



#### To build a docker image from the application

$docker build -t my-app:1.0 .      ## the dot at end of line it is represent to the current path of Dockerfile 

#### To start the application

1: start mongodb and mongo-express and app
 
$ docker-compose -f docker-compose.yaml up
    
2:to access the mongo-express on localhost:8080 from your browser_
    
3: in mongo-express - create a new database "my-db"

4: in mongo-express - create a new collection "users" in the database "my-db"       
        
5: to access the nodejs application from browser on http://localhost:3000

  
    

    