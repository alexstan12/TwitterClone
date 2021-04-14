# TwitterClone

## A project I made for learning Spring Boot , ORM with Spring Data

This project replicates some basic functionalities of Twitter, including :
 - Creating users, posts, replies
 - Following users
 - Liking posts
 - Replying to posts
 - Getting a post feed for a specfic user
 - Finding users based on id/name
 - Deleteing users and posts
 - many more...
 
## Tech stack and tech related info :
 This is a server application based on SpringBoot that exposes several REST APIs with functionalities afore mentioned.
 - uses Controllers, Services, Models, Repositoriers (which extend CrudRepository)
 - MySql as a database
 - ORM with Spring Data
 - Server running on Tomcat9 (embedded)
 - API calls made with Postman
 
Project logic structure:
![](https://i.ibb.co/60W0B3Q/Twitter-Project-Specifications-2-3.jpg)
