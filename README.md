#What is JSON Web Token?

JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed. JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.

![image](https://github.com/swati-wanjari/spring-security-jwt-example/assets/146084843/d2687670-7ce7-4ae7-ae63-6fd5eafcd4af)

in server side application we add spring security

![image](https://github.com/swati-wanjari/spring-security-jwt-example/assets/146084843/7f0c0b53-a7fa-4ed7-b885-760f9faa8f8b)

Instead of giving hardcoded username and password in each and every request you can pass your encrypted string which is called JSON Web Token.

JWT is self contained
It contains your input in encrypted format (uername and password) + other fields (refer jwt.io) official doc.

JWT contains 3 part
![image](https://github.com/swati-wanjari/spring-security-jwt-example/assets/146084843/fc9f0a92-a6a2-4843-9e39-dfcbaea34ece)

Header + Payload + Verify Signature (separated by dot(.))
<h5>Header</h5>
specify which type of algorithm you are using + which type token we are using
<h5>Payload</h5>
user details
<h5>Verify Signature</h5>
Header+Payload  encrypted in base64url

<h3>Dependencies</h3>
Lombok \n
Spring Web
Spring Security
H2 database
Spring Data JPA
spring-boot-devtools



