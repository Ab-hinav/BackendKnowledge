# What is Http ?
- Protocol to communicate b/w web servers & clients.


## Http is stateless -> doesn't remember anything from before.

## What is Https ?
- HTTP Secure
- Data sent is encrypted
- SSL/TLS -> secure layer
- Install certificate on web host

## HTTP method
- GET -> retrieves data from server

- POST -> submit data to server

- PUT -> update data already on the server

- DELETE -> delete data from server


## Http header fields

- GET /tutorials/other/topic1/ HTTP/1.1
Host:
User-Agent:
Accept:
Accept-Language:
...

General:
Request URL
Request Method
Status Code
Remote Address
Referrer Policy

Request:
Cookies
Authorization


## HTTP Status Code
 
- 1XX: Informational -> request recieved/processing
- 2XX: Success -> sucessfully recieved,understood accepted
- 3XX: Redirect -> further action must be taken/redirect
- 4XX: Client error -> request does not have what it needs
- 5XX: Server Error -> server failed to fulfil an apparent valid request

-- 200 -ok, 201 - ok created, 301-moved to new URL, 304-not modified, 400-bad request,401 - unauthorized,404 - not found,500 - internal server error



