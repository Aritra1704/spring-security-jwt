*  spring-security-jwt
Basic of Spring Security using JWT

# Reference from
https://www.youtube.com/watch?v=X80nJ5T7YpE&list=PLqq-6Pq4lTTYTEooakHchTGglSvkZAjnE&index=12&ab_channel=JavaBrainsJavaBrainsVerified

# How to test this code:
* Run the project
* Open Postman
* Set this Url: http://localhost:8080/authenticate
* Add Header: Content-Type  application/json
* Convert the api to POST request
* Run it.
* Find the jwt string in response
* Open another tab
* Set this Url: http://localhost:8080/hello
* Add Header: Authorization  Bearer <jwt received in authenticate API>
* Convert the api to GET request
* Run it.
