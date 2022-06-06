# Login Registration Backend 

Login registration backend demo using Spring Boot.


-  Spring Boot
-  Spring Security
-  Java Mail
-  Email verification with expiry




## Email verification link with expiry
![MailDev](https://user-images.githubusercontent.com/82181439/172172992-56b9dee1-bf3f-4291-bac7-383121dc2a35.png)

## Example requests
### Postman

![Postman Request](https://user-images.githubusercontent.com/82181439/172172266-b0b15413-add0-4dd1-965e-5f87e3ae472a.png)



### CURL
```
curl --location --request POST 'localhost:8080/api/registration' \
--header 'Content-Type: application/json' \
--data-raw '{
    "firstName": "firstName",
    "lastName": "lastName",
    "email": "firstLast@email.com",
    "password": "password"
}'
```
