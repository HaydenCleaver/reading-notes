# Class 7

Node is a flexible and powerful runtime environment that allows us to utilize a large kit of tools to help with software development

## Intro to JWT

1. What is a JSON Web Token (JWT)?

    * A self contained way for securely transmitting info between parties as a JSON object.
        * Digitally signed using a secret or public/private key pair using RSA or ECDSA (which utilize HMAC algorithm).
        * Signed tokens verify integrity of the data within, while encrypted tokens hide the data.

2. When should we use JSON Web Tokens?

    * JSON Web Tokens are commonly used in situations that require authorization and information exchange due to their uses in verification and encryption.

3. Claims are expected in which structural component of a JWT?

    * Claims are found in the second part of the token, which is called the Payload.

    [JWTs](https://jwt.io/introduction/)

## Are JWTs Secure?

1. If I get a JWT and I can decode the payload, how can we call that secure?

    * If I understand correctly, it's because by changing the content of the JWT, you would alter the signature which means the receiving party would notice the change and disregard the JWT as invalid.

2. If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.

    * Both parties must know the secret.

3. Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

    * The content and secret of a JWT are bundled together and obscured by a hash code, which needs to be translated by a key that the user and sender have.

    [Stack Overflow: JWTs](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)

## JWTs Explained

1. Why use JWT?

    * To securely transfer information between two bodies.

2. JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.

    * It makes it very fast to transmit and can be sent in a variety of methods thanks to its size.  It also contains info about the user itself and helps avoid reptitious querying of data.

3. What are the three components (the structure) of a JWT signature?

    * Header, Payload, Signature

[What is JWT?](https://www.youtube.com/watch?v=926mknSW9Lo)

[Return to Table of Contents](https://haydencleaver.github.io/reading-notes/)