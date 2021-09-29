# real_time_chat
A real time chat app built with Go

#This is an example cURL request for testing the endpoint:
```
curl --location --request POST 'http://localhost:8000/api/messages' \
--header 'Content-Type: application/json' \
--data-raw '{
    "username": "Pedro Coelho",
    "message": "Hello"
}'
```