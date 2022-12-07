Run In Terminal
npm install

whatsapp-api-nodejs
create with nodejs
"node@16.16.0"
"npm@8.11.0"

dependencies module
"nodemon"
"body-parser": "^1.20.1",
"express": "^4.18.2",
"qrcode-terminal":
"^0.12.0",
"whatsapp-web.js":
"^1.18.4"

How to running
open terminal
nodemon app
scan your qrqode
http://localhost:3000/api?nohp=08xxxxxxxx&pesan=lorem%20ipsum
or open your postman
method post in postman

status success
{
"status": "success",
"pesan": "lorem ipsum"
}

status field
{
"status": "field",
"pesan": "number unregistered"
}

status error
{
"status": "field",
"pesan": "error server"
}
