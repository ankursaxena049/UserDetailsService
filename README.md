**# UserDetailsService

---------------------------------------------------------
Credentials for Basic Authentication:

User Id: AmdocsUser1
Password: AmdocsUser1

User Id: AmdocsUser2
Password: AmdocsUser2

----------------------------------------------------------

URL: http://localhost:8081/assignment/
----------------------------------------------------------
@Get: (Get User Details by Id)
URI: http://localhost:8081/assignment/user/1001
----------------------------------------------------------
@Post: (Create New User)
URI: http://localhost:8081/assignment/user/
Input: 
{
    "id": 10015,
    "userName": "Ankur Saxena",
    "password": "pass@123",
    "status": "Activated"
}
----------------------------------------------------------
@Put: (Update User Details)
URI: http://localhost:8081/assignment/user/
Input: 
{
    "id": 10015,
    "userName": "Ankur Saxena",
    "password": "pass@123",
    "status": "Deactivated"
}
---------------------------------------------------------
@Delete: (Delete the Resource by Id)
URI: http://localhost:8081/assignment/user/1001
**
