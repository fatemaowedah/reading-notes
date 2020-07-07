###  Login and Auth
####  ContextAuthentication + Role Based Authorization
we check if the valid user is loggend in and what is the user authorized to do, Which parts care about this, What’s in the token,Contact between the UI and the API, How do we make this easy to use , `<Auth />` it about permissions and login status,give access to a component or jsx or hides it, we dont use redux don’t want to force implementors into a specific state management system.
####  what is rbac?
Role-based access control access based on a person's role within an organization , The roles in RBAC refer to the levels of access that employees have to the network,Employees are only allowed to access the information necessary to effectively perform their job, access to computer resources can be limited to specific tasks such as the ability to view, create, or modify a file, user is an administrator, a specialist user, or an end-user, and align roles and access permissions with your employees’ positions in the organization. Permissions are allocated only with enough access as needed for employees to do their jobs: Management role scope, Management role group, Management role, Management role assignment, options for user access may include: Primary, Billing, Technical, Administrative, there is a benefits: Reducing administrative work and IT support, Maximizing operational efficiency, Improving compliance, best practice for implementing RBAC: Current Status, Current Roles, Write a Policy, Make Changes, Continually Adapt.
####  react-cookies component
you can install it `npm install react-cookies --save`, you can load cookie value, Returns undefined if the cookie does not exist by `.load(name, [doNotParse])`, Load all available cookies, Returns an object containing all cookies `.loadAll()`, Find all the cookies with a name that match the regex,Returns an object with the cookie name as the key `.select([regex])`, to set a cookie `.save(name, value, [options])` name: is a string and require, value: string||number||object, options: object, path:Cookie path, Use / as the path if you want your cookie to be accessible on all page string, Load the user cookies so you can do server-rendering and match the same result `.plugToRequest(req, res): unplug()`, Load the user cookies so you can do server-rendering and match the same result `.setRawCookie(cookies)`.
####  react-cookie library
we can get start by: npm install react-cookie, you can Set the user cookies by `<CookiesProvider />`, Access and modify cookies using React hooks. by `useCookies([dependencies])` the dependencies is optional,Set a cookie value:`setCookie(name, value, [options])`;name (string): cookie name,value (string|object): save the value and stringify, options (object):: path (string), expires (Date), maxAge (number), domain (string), secure (boolean),httpOnly (boolean),sameSite (boolean|none|lax|strict), Remove a cookie:::by `removeCookie(name, [options])` name (string): cookie name, options (object):: path (string), expires (Date), maxAge (number), domain (string), secure (boolean),httpOnly (boolean),sameSite (boolean|none|lax|strict), Give access to your cookies anywhere by ::: `withCookies(Component)`, cookies: Cookies instance allowing you to get, set and remove cookies, allCookies: All your current cookies in an object.
















