# API Testing Project for Reqres
The scope of this project is to use all API knowledge gained throught the Software Testing course and apply them in practice, using a live application.<br>
Application under test: Reqres<br>
Tools used: Postman, Newman<br>
Collection link: [link](https://github.com/SimonaGheorghe/API-Testing---PostMan/blob/main/README.md) <br> 

# Tests performed <br>
<ol>
<li>List Users</li>
HTTP method for request: <strong>GET</strong>
Request description: The request type indicates that the client is requesting data from the server. In this case, the client wants to retrieve a list of users. <br> 
Response status code: 200 OK <br> 
Below you can find a picture of the API request from Postman:<br> 
<img width="644" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/69ad1486-5f82-46ed-9b66-4258d41f1825"><br>
JavaScript Tests: <br> 
<img width="639" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/efd6000d-1e8f-4a8f-96a0-6815676723de"> <br> 
<img width="646" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/1703e630-06c7-4d44-bd3a-ba6cfe91bfaf"> <br> 
<img width="650" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/a2b35ff0-74b8-442b-9c4f-dd3854cc540b"> <br> 

  <strong><li>List Single User</li></strong>
HTTP method for request: <strong>GET</strong>
Request description: The request type indicates that the client is requesting data from the server. In this case, the client wants to retrieve user data for the user with ID 5. <br> 
Response status code: 200 OK  <br> 
Below you can find a picture of the API request from Postman:<br> 
<img width="651" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/bcf3eff2-94e8-4b06-8534-72cc013ca73a"> <br> 
JavaScript Tests: <br> 
<img width="644" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/8276e327-ef12-4d50-a17e-806a84d77eab"> <br> 
<img width="638" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/25934550-d8d7-4cc7-90c5-a820c18a252b"> <br> 
  
  <strong><li>Create User</li></strong>
HTTP method for request: <strong>POST</strong>
Request description: This request is sending data to the server to create a new resource. In this case, to create a new user by sending user data to the server. <br> 
Response status code: 201 Created <br> 
Below you can find a picture of the API request from Postman:<br> 
<img width="641" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/7dbf431b-c476-44c2-a7e0-d878d88f5872"> <br> 
JavaScript Tests: <br> 
<img width="625" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/a58944b7-d27a-4f39-ae56-22c1fa1d3237"> <br> 
<img width="630" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/b8bb46f1-59a9-49e5-a214-21fae0b5d099"> <br> 
<img width="637" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/c5f8be33-52c0-4779-8867-3c506240f2ac"> <br> 

  <strong><li>Update User</li></strong>
HTTP method for request: <strong>PUT</strong>
Request description: This request is sending data to the server to change an existing resource. In this case, to modify the user id 5 by sending user data to the server. <br> 
Response status code: 200 OK <br> 
Below you can find a picture of the API request from Postman:<br> 
<img width="644" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/3e84d2e0-06fa-4bdf-9175-58c4ff5b85a6"> <br> 
JavaScript Tests: <br> 
<img width="627" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/2ee450d6-ab22-406c-be52-afc48cccf732"> <br> 
<img width="635" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/33b829d4-b5da-43ad-8ba8-53c9f4392c74"> <br> 

  <strong><li> Detele User</li></strong>
HTTP method for request: <strong>DELETE</strong>
Request description: This request is sending data to the server to delete a resource. In this case, to delete the user id 5. <br> 
Response status code: 204 No Content  <br> 
Below you can find a picture of the API request from Postman:<br> 
<img width="635" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/f6ad45e6-2c99-46a0-9079-ca9fa19ca59a"> <br> 
JavaScript Tests: <br> 
<img width="647" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/f6e8008d-c3e5-44cb-a0d0-823258e9c6f7"> <br> 

  <strong><li> Register Successfully</li></strong>
HTTP method for request: <strong> POST </strong>
Request description: By sending this request in Postman and providing the necessary registration data in the request body, the client can initiate the registration process with the server. The response returned by the server will indicate the success or failure of the registration attempt, along with any additional information provided by the API.. <br> 
Response status code: 200 OK  <br> 
Below you can find a picture of the API request from Postman:<br> 
<img width="614" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/fe1377d6-693c-4af1-a801-d03852e0aedd"> <br>
JavaScript Tests: <br> 
<img width="634" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/a2c96f6c-0c1e-4453-af2f-a857433c6b02"><br> 

  <strong><li> Register Unsuccessfully </li></strong>
HTTP method for request: <strong> POST </strong>
Request description: By sending this request in Postman and providing the necessary registration data in the request body, the client can initiate the registration process with the server. The response returned by the server will indicate the success or failure of the registration attempt, along with any additional information provided by the API.. <br> 
Response status code: 404 Bad Request   <br> 
Below you can find a picture of the API request from Postman:<br> 
<img width="622" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/0d6cb041-b0e4-45db-b7f4-048c5dff8dad"> <br> 
JavaScript Tests: <br> 
<img width="631" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/b9ca9d89-5e84-4ba6-b30a-2625b0a8a0ad"> <br> 
  
<strong><li> Login Successfully</li></strong>strong>
HTTP method for request: <strong> POST </strong>
Request description: By sending this request in Postman and providing the necessary login data in the request body, the login action is done successfully. The response returned by the server will indicate the success or failure of the login attempt. <br> 
Response status code: 200 OK  <br> 
Below you can find a picture of the API request from Postman:<br> 
<img width="632" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/eb68dd59-7c2b-4560-aa4d-59643c436031"> <br> 
JavaScript Tests: <br> 
<img width="629" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/a64d6275-1e83-4850-bae4-57fc2adc1be7"> <br> 
  
<strong><li> User not found</li></strong>
HTTP method for request: <strong> GET </strong>
Request description: This request type indicates that the client is requesting data from the server. In this case, the client is attempting to retrieve user data for a user with ID 400 (which does not exist). <br> 
Response status code: 404 Not Found <br> 
Below you can find a picture of the API request from Postman:<br> 
<img width="635" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/8a057749-15a1-4b4e-8617-92350ee8b095"> <br> 
JavaScript Tests: <br> 
<img width="648" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/83ccfbee-ee85-41cf-b390-743f2b000ea5"> <br> 
<img width="633" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/6017165a-04f5-4793-96c8-135573404255"> <br> 

<strong><li> Update User </li> </strong> 
HTTP method for request: <strong> PATCH </strong>
Request description: This request updates the user data for the user with ID 12. <br> 
Response status code: 200 OK <br> 
Below you can find a picture of the API request from Postman:<br> 
<img width="640" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/5d072140-a97e-4a9c-837b-84654ed995a1">
JavaScript Tests: <br> 
<img width="662" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/dad4165c-4a24-4711-8cf6-95cabe08ac31"> <br> 
<img width="635" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/d3a3d66f-dcd4-4bd7-bd2b-6d5a5c9c341e"><br> 
<img width="632" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/80a11d18-0991-4d9f-9056-6058cf872c6b"> <br> 

<strong><li> Get specific user by name </li> </strong> 
HTTP method for request: <strong> GET </strong>
Request description: This request select a specific user by the name data registred. In this case, for user name Emma. <br> 
Response status code: 200 OK <br> 
Below you can find a picture of the API request from Postman:<br> 
<img width="634" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/82cf675c-53fa-491b-9104-13b4c5acc9ab"> <br>
JavaScript Tests: <br> 
<img width="644" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/ace56172-d797-4dde-88de-2f7eebd1021a"> <br> </ol>

## Execution report for the created API collection <br> 
Below you can find the execution report that was generated through the Postman collection runner: <br> 
<img width="659" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/0d69b0c2-b78e-4231-a6cb-4df137436471"> <br> 
The collection was also run through newman directly from the terminal, and the results can be found below:<br> 
<img width="486" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/96757fe6-cdfc-4b5f-a4bc-4cc9e262b871"> <br> </ul>

## Defects found
Title: Login successfully even if the password is not correct<br> 

Precondition: The email and the password need to be correct in order to login and the status code to be 200 OK <br> 

Reproduction Steps: <br> 
<ul> <li>. Open Postman.</li>
<li>.Ensure you are on the "Request" tab.</li>
<li> In the URL bar, enter https://reqres.in/api/login.</li>
<li> Select "POST" as the HTTP method from the dropdown menu next to the URL bar.</li>
<li> Click on the "Body" tab below the URL bar. </li>
<li> In the "Body" section, select the "raw" radio button.</li>
<li>From the dropdown menu next to the "raw" radio button, select "JSON". </li>
<li> In the text area below, enter the JSON object representing the login credentials.</li>
<li> After entering the JSON object, click on the "Send" button located on the right side of the URL bar. </li>
<br> 
Expected Results: Postman will send the POST request to https://reqres.in/api/login with the provided login credentials in the request body.
Once the server responds, the response will be displayed as 401 Unauthorized. <br>

Actual Results: The response is 200 OK, even if the password is not correct. <br> 

<img width="645" alt="image" src="https://github.com/SimonaGheorghe/API-Testing---PostMan/assets/163425980/96722d47-b71b-4f9d-9fcf-314596b5371d">  <br> 

## Conclusions

In conclusion, through a series of 25 tests encompassing 11 distinct requests, several key observations and conclusions have emerged:
<li> Utilizing Postman to interact with the ReqRes API provides a streamlined approach for testing and validating API endpoints. Through Postman, developers can easily send various HTTP requests, such as GET, POST, PATCH, and more, to the ReqRes API endpoints and examine the responses. </li> 
<li> The clarity and comprehensiveness of the ReqRes API documentation played a crucial role in facilitating the testing process. Clear documentation aided in understanding the API's capabilities, request formats, and expected responses, thereby enhancing usability and developer experience. </li>
<li> A critical bug has been identified wherein unauthorized users can gain access to other accounts, even with incorrect passwords.</li>
