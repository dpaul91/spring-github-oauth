# spring-github-oauth
spring security using github oauth
Steps :

1)Create a GitHub App and get the Client ID and Client Secret values. 
 -Specify callback URL as http://localhost:8080/login/oauth2/code/github for development, uncheck Web hooks
2)Add those values in application.yml(Client-ID and client-secret)
3)Run the Spring Boot App. You should be able to login with GitHub
4)Rest call: http://localhost:8080/user

youtube reference: https://www.youtube.com/watch?v=nwyf_4aSkqM&list=PLJ5_m4Y8xLkkxfo2Z1Lb0qjXnAZqIWCCZ&index=11 
