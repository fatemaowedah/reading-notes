### OAUTH2.0
#### OAUTH2.0
it have a role; Client,Resource Server, the Authorization server, Resource Owner, to create an app ou must first register a new app with the service, after that it will redirect URI to be used for redirecting users.
#### Oauth
is an open standard foe access delegation, way for Internet users to grant websites or applications access to their information on other websites but without giving them the passwords, it give the ability to grant access to services without giving the application their password, it is look like the dialoge box which pop-up to login with google or github, when you login in that mean you give the application you give the app key to some of you personal information and access some level at google.
#### How does OAuth work?
there is a series of handShakes the app ask the user if it is ok to login, after that the application pop-up window login using and ask for specific permissiona when the user agree, then the service contact the app using the code and this app callback to special address and change this code to a token after that they use token to access information.
#### Access Code
the client give the permission for the app you need a tag which transfer you to service’s authorization page, the information pass as a query string, variables are part of initial request;response_type: server want to receive an authorization code, client_id: tell erver which app the user is granting access to, redirect_uri: endpoint to redirect to, scope: what you want the user to give access to, state: where you can store info to pass to your server if you want.
#### Access Token
if the user gice access to application authorization server will redirect it with code, when you have this code you exchange it to access token by making POST req and give this information; grant_type: authorization_code, redirect_uri: the same URl the client provide, client_id: which application is making the requests, client_secret: you can use it to make API calls.



