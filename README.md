# OAuth2App

Simple REST API based on JWT (without Spring Security module).
User stores data about login and password. In POST web method JWT is built based on the User.
JWT contains also information about user roles, life length of token. With the token it is possible to
access resource (GET method web). The method is captured by filter which validates the correct token.
