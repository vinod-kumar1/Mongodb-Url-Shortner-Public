Hey There 👋

This project includes 2 folder -> client and server-auth

Steps to deploy the server-auth project

1. Add env vairalbles and connect to your db.
2. npm install & test locally
3. Deploy. (I've used vercel)
4. Make a note of the deployed site as we'll be using that enpoint as API to make POST/GET requests from client

Steps to deploy the client side code

1. Clone it & test loally if HTML page is rendering properly
2. Now inside the public/apper.js file use the server deployed site url in fetch request and replace your server url wherever necessary
3. Here are some docs I've followed when I face CORS issues : 
https://www.mongodb.com/docs/atlas/security/ip-access-list/
https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS

I know I said its a shorturl project but its generating a long ugly url but I've deployed my server in vercel and I have to use that url as endpoint. I'll try to imporve it 🫡
