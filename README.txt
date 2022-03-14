Following a guide from Sam Barros, 2019.   MERN stack.
https://medium.com/swlh/how-to-create-your-first-mern-mongodb-express-js-react-js-and-node-js-stack-7e8b20463e66
I've named my project mern-stack-barros-backend, instead of movies-app


To run:
1.  CD TO SERVER FOLDER !!
2.  $ node index.js

(( 3. In theory, should be able to do $ nodemon index.js, and then app listens for changes, but it's not working))


To connect to my Atlas cluster for this project:
(see .env for username, user-password)
mongosh "mongodb+srv://<username>:<user-password>@mern-stack-barros-clust.0gjsv.mongodb.net/admin"


To add a movie to our database via postman:
http://localhost:3000/api/movie
POST
Body (json):
{
    "name": "Avengers: Endgame",
    "time": ["14:15", "16:00", "21:30", "23:00"],
    "rating": 8.8
}



"We need to create a connection from our server using the Mongoose library."
See Explanations Bookmark for how to handle process.env, and the .env file

---- ---- --- ----- ----- ----- ----- 
---- ---- --- ----- ----- ----- ----- 

Eexists a branch of this project called:
backend-complete-oxbow

If I never do anything with this project again, this oxbow and main will 
remain pretty similar


---- ---- --- ----- ----- ----- ----- 
---- ---- --- ----- ----- ----- ----- 

I AM STARTING A NEW PROJECT BASED ON THIS ONE, FOR THE CUBE
IT IS FILED UNDER CUBE/INTERACT-SENTENCES-DADDY
I INTEND IT TO BE PART OF A TWO-APP PROJECT:
  - FRONT-END IS CALLED "INTERACT-WITH-SENTENCES-WEB-APP-ONE"
  - BACK-END IS CALLED "INTERACT-WITH-SENTENCES-MERN-MONGODB"
