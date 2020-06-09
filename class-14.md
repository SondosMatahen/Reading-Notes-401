## Access Controls:
- Access Controls are the selective restriction of resources. Access Controls are implemented everywhere in computer systems. UNIX files have read, write, and execute permissions assigned to owners, groups, and everyone else. 
- Websites have limited access to pages based on the credentials of a user. APIs restrict access to internal and external developers differently.

## Application Flow and Access Control:
- A CMS  might be able to:
- Allow admin users to create categories, content, manage user accounts, and run reports
- Allow editor users to create, edit and delete existing content, but not see or manage user accounts
- Allow guest users to access (read) content
- Allow user users (logged in users) to access (read) content and apply a thumbs-up/down to content, but not change the actual content

## Back End (API Layer)
- Manage the login cycle with the front-end application
- Maintain the User’s database
- Maintain roles for each user
- Authenticate users (basic and bearer)
- Create, manage, and apply Role Based Access Controls
- Maintain and reference their capabilities, based on their role
- Restrict access to features (like routes) based on capabilities
- Express Middleware could be used to restrict access to routes
- Mongoose Middleware/Hooks could be use to restrict access to business logic

## Front End (Client Layer)
- Initiate the login process
- Store login tokens as cookies
- Manage login state, capabilities
- Control physical & visual access (hide/show/alter) to components based on RBAC rules
- Alter behaviors based on RBAC rules


## Role-based access control (RBAC):
- it is a method of restricting network access based on the roles of individual users within an enterprise.
- RBAC lets employees have access rights only to the information they need to do their jobs and prevents them from accessing information that doesn't pertain to them.
