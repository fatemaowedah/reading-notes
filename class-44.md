### Access Control (ACL)
#### Access Controls
selective restriction of resources, website have limited access to pages base on the credentials of a user, APIs restrict access to internal and external developers differently, RESTful it limit the access for client based on credentials such as the user can't delete other user, for that we do access control to limit what action a uuser can preform, when the user signup and login this token pass with the req the server from the token it can detrmine if the user is authorize to preform the request.
#### Application Flow and Access Control
application have varying degree of access based on user type and the reqirement, and this type is: Admin it allow to create categories, content, manage user accounts and run report, Editor: allow create, edit, delete existing content, not see or manage account, Guest: allow user to access read content,User to access and read content and apply thumbs-up/down to content, 
#### Back End (API Layer)
manage the user database, login cycle with front-end application, maintain roles, authienticate user, create manage, and applay role, maintain and refe, restrict access to feature, express midldleware,mongoose middleware/hooks.
#### Front End (Client Layer)
initiate the login process, store login token as cookies, manage login state, control physical & visual access, alter behavios based on RBAC.
#### 5 steps to simple role-based access control (RBAC)
assigning system access to users based on their role in an organization, roles based on common job responsibilities and system access needs, the benifit of it is systematic, repeatable, easier to audit user right and fixed any issues identified it is easy and secure, if you want to implementation you follow this 5 step: Inventory your systems, Analyze your workforce and create roles, Assign people to roles, Never make one-off changes, Audit.

