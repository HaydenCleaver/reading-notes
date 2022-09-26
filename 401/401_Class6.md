# Class 6

Node is a flexible and powerful runtime environment that allows us to utilize a large kit of tools to help with software development

## Securing Passwords (Bcrypt)

1. Explain to a non-technical friend how you would safely hash and store a password.

    * The basic premise is that plain text passwords are taken and converted into "hashes" by a hash algorithm and then stored somewhere in a database to be used when appropriate.

2. What is Bcrypt?
    
    * Bcrypt is a hash function that's based on the Blowfish symmetric block cipher cryptographic algorithm.  It utilizes a work/security factor which lets you alter how expensive the hash will be.

3. Why might you use something like Bcrypt?

    * This is useful because it lets you determine how slow to make the hash function and makes it better at resisting brute force attacks.  It also means that it has scalability for the future, since it can be further slowed any time that faster processing units are developed.

    [Hacker News](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)


## Basic Auth

1. What is Basic Authentication?

    * It's a method that allows an application to assign a username and password to a user when making a request.

2. What properties are necessary in the header of a Basic Auth request?

    * `Authorization:Basic<Credentials>`, where crententials is the Base64 encoding of the ID and password joined by a `:`.

3. How are `username:password` in Basic Auth encoded?

    * It uses Base64, so it's converted to binary.  This means that it isn't really protected by something like a hash algorithm and should be paired with some sort of security measure.

    [Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)

## OWASP Auth Cheatsheet

1. Define the authentication process to a non-technical recruiter.

    * Authentication is the process of confirming that a user is who they say they are, typically by requiring their username and something else that only they should know (such as a password or security questions).

2. How should your error messaging respond (both HTTP and HTML)? Why?

    * It should always provide a generic response that covers all of the possible error factors.  This reduces the information provided to malicious users.

3. Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.

    * [https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)

## Things I want to know more about

I would like to dig into the email address validation information as well as the password storage information.

[https://cheatsheetseries.owasp.org/cheatsheets/Input_Validation_Cheat_Sheet.html#email-address-validation](https://cheatsheetseries.owasp.org/cheatsheets/Input_Validation_Cheat_Sheet.html#email-address-validation)

[https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html#maximum-password-lengths](https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html#maximum-password-lengths)

[Return to Table of Contents](https://haydencleaver.github.io/reading-notes/)