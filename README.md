Run your application and test it out. Hit the following URL:
http://localhost:8080/auth/addNewUser

It will add the user to the database.
{
    "name": "anshul",
    "password": "123",
    "email": "anshul@gmail.com",
    "roles": "ROLE_USER"
}

Hit the following URL for a token generation test:
http://localhost:8080/auth/generateToken

Hit the following URL and put the Bearer for testing access our endpoint according to the ROLE:
http://localhost:8080/auth/user/userProfile
