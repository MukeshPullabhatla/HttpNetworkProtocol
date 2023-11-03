# HttpNetworkProtocol
This is a simple HTTP Network Protocol

## Inorder to run this application locally:
Do `npm install --save express`

# GET Request
## Command
```
curl localhost:3000/hello
```
## Response
<img width="434" alt="image" src="https://github.com/MukeshPullabhatla/HttpNetworkProtocol/assets/71534604/58f19b25-ad83-444e-a5a8-bd6ef5631aeb">

# POST Request
## Command
```
curl --header 'content-type: application/json' localhost:3000/hello --data '{"foo": "bar"}'
```
## Response
<img width="209" alt="image" src="https://github.com/MukeshPullabhatla/HttpNetworkProtocol/assets/71534604/60cb8240-dad7-4a96-af37-99930748d8ad">

## HTTP
The HyperText Transfer Protocol is a very common network protocol implemented on top of TCP. Clients make HTTP requests, and servers respond with a response.

Request typically have the following schema:
```
host: string (example: algoexpert.io)
port: integer (example: 80 or 443)
method: string (example: GET, PUT, POST, DELETE, OPTIONS or PATCH)
headers: pair list (example: "Content-Type" => "application/json")
body: opaque sequence of objects
```

Response typically have the following schema:
```
status code: integer (example: 200, 401)
headers: pair list (example: "Content-Length" => 1238)
body: opaque sequence of bytes
```

