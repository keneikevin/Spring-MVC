# Spring-MVC
Using these endpoints you can test the project that registers students you can register a student and update or delete him/her using these endpoints


#To get list of all students

@GET request to get all students

https://heroku-moringa.herokuapp.com/api/v1/students


#To register a student

@POST request to register a student

https://heroku-moringa.herokuapp.com/api/v1/students/register
{
       "name":"name",
       "email":"email@gmail.com",
       "dob":"1995-12-17"
}




#To update a student

@PUT request to udate students info

https://heroku-moringa.herokuapp.com/api/v1/students/update/{studentId}/name={name}&email="email"





#To delete a student

@DELETE request to delete a student

https://heroku-moringa.herokuapp.com/api/v1/students/delete/{studentId}





