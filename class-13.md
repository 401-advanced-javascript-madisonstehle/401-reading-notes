# Class-13
## Bearer Authorization


### Links
- [What is JWT? JSON Web Token Explained](https://www.youtube.com/watch?v=926mknSW9Lo) (video)
- [Intro to JWT](https://jwt.io/introduction/)
- [Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)
- [NPM JSON Web Token Documentation](https://www.npmjs.com/package/jsonwebtoken)
- [3 Common Methods of API Authentication Explained](https://nordicapis.com/3-common-methods-api-authentication-explained/)


### Discussion Questions
1. **When is Basic Authorization used vs. Bearer Authorization?** Basic Authorization is not as secure as Bearer Auth. If you're going to have a simple web page with not much sensitive information involved, basic auth is fine, but bearer auth is more thorough and should be used when there is sensitive information being passed between clients and servers. Basic could be useful in an internal network.
2. **What does the JSON Web Token package do?** It is a common way to generate tokens. It is a standard that describesa way to secure transmit information between two systems as a JSON object.
3. **What considerations should we make when creating and storing a SECRET?** It should be well hidden and protected because it can be used to decrypt sensitive information.


#### [Back to Home](README.md)