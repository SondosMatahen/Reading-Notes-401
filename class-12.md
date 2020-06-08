## OAuth 02  (Authorization between services) 
- is an open standard for access delegation
-  OAuth serves as a way to give users the ability to grant application access to services, without giving the application their password.  

## OAUTH 02:
- is a protocol that allows a user to grant limited access to their resources on one site, to another site, without having to expose their credentials.

## How does OAuth work?
- there is a series of handShakes the app ask the user if it is ok to login, after that the application pop-up window login using and ask for specific permissiona when the user agree, then the service contact the app using the code and this app callback to special address and change this code to a token after that they use token to access information.

## Access Code
- An identification number and/or password used to gain access into a computer system.
- The number used as a prefix to a calling number in order to gain access to a particular telephone service.

## Access Token
- if the user gice access to application authorization server will redirect it with code, when you have this code you exchange it to access token by making POST req and give this information; grant_type: authorization_code, redirect_uri: the same URl the client provide, client_id: which application is making the requests, client_secret: you can use it to make API calls.
