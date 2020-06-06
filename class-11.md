## User Modeling:
- User models that have sensitive data that should NEVER be sent to client applications. If your application requires that users be able to read each others personal information, create a second Profile model to hold that data and strictly limit access to the Profile model.
- Safely using a second model will ensure that no users will accidentally get access to sensitive information.

## Cryptography:
- Cryptography is the science which studies methods for encoding messages so that they can be read only by a person who knows the secret information required for decoding the key it includes cryptanalysis the science of decoding encrypted messages without possessing the proper key and has several other branches.

## Hash Algorithms:
- A Cryptographic Hash Algorithm takes a piece of data and produces a hash that is deliberately difficult to reverse. If identical data is passed into the algorithm the same hash will always be produced.
- Hash algorithms are often used for checking the integrity of data.

## Cypher Algorithms:
- A Cryptographic Cypher Algorithm takes a piece of data and a key and produces encrypted data. Later the encrypted data can be reversed into the original data by decrypting it using the same key.

## Basic Authorization:
- Basic Authorization is a common method used to send a username and password in an HTTP request.
- The username and password are joined with a ‘:’ then “base64 encoded” and placed after the string ‘Basic ‘ The resulting string is set to the value of an Authorization header.
