## Whatsapp Gateway (Started Project)

### Run In Terminal
`npm install`

### whatsapp-api-nodejs
create with nodejs
- "node@16.16.0"
- "npm@8.11.0"

### dependencies module
- "nodemon"
- "body-parser": "^1.20.1",
- "express": "^4.18.2",
- "qrcode-terminal":"^0.12.0",
- "whatsapp-web.js":"^1.18.4"

### How to running
1. open terminal
`nodemon app`
1. scan your qrqode
1. open browser and type url http://localhost:3000/api?nohp=08xxxxxxxx&pesan=lorem%20ipsum
1. or open your postman with url http://localhost:3000/api method post
```json
{
"nohp": 08xxxxxxxx,
"pesan": "Lorem ipsum dolor sit amet"
}
```

### status success
```json
{
"status": "success",
"pesan": "lorem ipsum"
}
```

### status field
```json
{
"status": "field",
"pesan": "number unregistered"
}
```

### status error
```json
{
"status": "field",
"pesan": "error server"
}
```
