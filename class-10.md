# Class-10
## Authentication


### Links
- [Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)
- [Bcrypt Documentation](https://www.npmjs.com/package/bcrypt)
- [Introduction to JWT](https://jwt.io/introduction/)

### Vocabulary
- **authentication**: the process of determining if someone is who they say they are - failure throws a 401 error
- **authorization**: are you able to see what you ask to see or have access to what you want - failure throws a 403 error
- **encryption**: two-way, uses a key to go from string to gibberish and back to string if needed
- **hashing**: one-way, the same string will always hash to the same gibberish - we are using [`bcrypt`](https://www.npmjs.com/package/bcrypt)
- **session**: 
- **cookie**
- **token**
- **Basic Auth**
- **encoding**: simple language translation to protect against special characters in usernames/passwords. Not encryption
- **secret**
- **cryptography**

### Discussion Questions
1. **Why is authentication important?** So that sensitive personal identifying information doesn't get into the wrong hands.
2. **Why should we be careful about storing a user’s password?** Because people (even devs working on the site) could gain access to that and use the informatiion in a malicious way.
3. **What is the difference between hashing and encryption?** Hashing is a type of encryption algorithm method used to secure data, usually passwords
4. **What is the difference between encryption and encoding?** Encryption is for maintaining data confidentiality and requires the use of a key to decrypt the information. Encoding is not used for securing data, but is used to transform data into a more readable form for systems or external processes. 
5. **What is a token used for?** A token is used to verify the encrypted data.


#### [Back to Home](README.md)