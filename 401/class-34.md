# Class 34 Reading Notes:

## Review API Server Build

### Explain the difference between a query string parameter and a path parameter.
Query string parameters are added to the URL after a question mark and separated by ampersands.

### What would our API URL with a path id parameter be given the following information:

Domain: http://our-site.com\
Version: v3\
Model name: stuff\
ID: things\
The URL would be: http://our-site.com/v3/stuff/things

### We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.
The API is designed to provide us with the information we need to run our system. We send requests to the API to let it know what information we need it to send or receive.

## Review Auth Server Build

### Describe how you would use middleware to implement basic and bearer auth.
Basic authorization will run on the /signin route, sending a POST request with the username and password. The password should be hashed and saved to a database.

### Describe the handshake necessary to implement OAuth.
The OAuth handshake begins with the client application directing the user to the authorization server, where the user authenticates and grants access, resulting in the issuance of an authorization code. The client then exchanges this code for an access token by making a request to the authorization server's token endpoint. Finally, the client uses the access token to access the user's resources on the resource server, and can optionally use a refresh token to obtain a new access token when needed.

### Describe how Role Based Access Control works to a non-technical friend.
Role-Based Access Control limits what you can do and access in a web system based on your role. For example, a CEO will probably have unlimited access, while lower-level employees will have more limited access.








