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

