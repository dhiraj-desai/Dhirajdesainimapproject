# <a href="https://clientuserprojectsapp.onrender.com/clients/">UserClientProject</a>


## 1] Users with username and tokens 
dhiraj

b76ff47569b86e1e67619bbe6ba6e303dfdd0315


ramesh

71fbf448663f869d2d95444db216a5d45cbc60c1


mangesh

7a120fb216e9fb3b3641406949b884582378096d


soham

80b0280564aaada4b6da845f41edd1df6dabd578


chintu

966b71135031bb8994d43a731e653a46bad7e484



## 2] you need to Test APIs in postman
#### Pass Token in headers

Key : Authorization 

Value : Token token_put_here

#### i.Create Client
POST request - https://clientuserprojectsapp.onrender.com/clients/

need token

Input:

{

    "client_name": "Test Client5"
    
}



#### ii. List all clients
GET request - https://clientuserprojectsapp.onrender.com/clients/


#### iii. Specific Client
GET request - https://clientuserprojectsapp.onrender.com/clients/3


#### iv. Create Project
POST request - https://clientuserprojectsapp.onrender.com/clients/4/projects/

Need Token

Input:

{

    "project_name": "Project Test2",
    
    "users": [
    
        {
        
            "id": 1
           
        }
    ]
}

#### v. Update Client Info
PUT request - https://clientuserprojectsapp.onrender.com/clients/4/

Input:

{
    "client_name": "Test Client5 Upgraded"
}

#### vi. Delete Client
DELETE request - https://clientuserprojectsapp.onrender.com/clients/4/

#### vii) Project assigned to logged in user
GET request : https://clientuserprojectsapp.onrender.com/projects/

Need token
