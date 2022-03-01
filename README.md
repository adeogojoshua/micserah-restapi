# micserah-restapi
A NodeJS RestAPI

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. All routes are of the POST request type.


## Clone the repository, install node packages  and verify routes locally

``` 
git clone https://github.com/adeogo/micserah-restapi
cd micserah-restapi
npm install
npm start
```

User and Feed data are loaded in an array(to simulate a database) in the resources folder


Open your api environment and verify the micserah-restapi is working by making post request to:     
`http://localhost:3000/`   
`http://localhost:3000/posts`   


Available endpoints are:  
`http://localhost:3000/`   
`http://localhost:3000/register`
`http://localhost:3000/post/2`
`http://localhost:3000/posts`  
`http://localhost:3000/posts/2`
`http://localhost:3000/profile/bret`


To fetch all users
`http://localhost:3000`

To register a new user
`http://localhost:3000/register`

``` 
{
 "name": "Adeogo",
 "username": "adeogo",
 "email": "ade@email",
 "phone": "2425252525",
 "interests": [
  	"swimming",
    "boxing"
 ]
  
}
```
