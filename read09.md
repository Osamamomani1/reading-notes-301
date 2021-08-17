# Review, Research, and Discussion

## What header(s) are used in authentication and authorization
 
 The WWW-Authenticate and Proxy-Authenticate response headers define the authentication method that should be used to gain access to a resource. They must specify which authentication scheme is used, so that the client that wishes to authorize knows how to provide the credentials.

 ***

 ## What is safe to put into a JWT

 inside the cookie

 ***
 ## How are JWTs validated

 The last segment of a JWT is the signature, which is used to verify that the token was signed by the sender and not altered in any way. The Signature is created using the Header and Payload segments, a signing algorithm, and a secret or public key (depending on the chosen signing algorithm).

 *** 

 * `RBAC`>>> Role-based access control (RBAC) restricts network access based on a person's role within an organization and has become one of the main methods for advanced access control. The roles in RBAC refer to the levels of access that employees have to the network.

 * `User Roles`>>> User Roles are permission sets that control access to areas and features within the Professional Archive Platform. Each User account requires a Role assignment.

 * `JWT Token`>>> JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.