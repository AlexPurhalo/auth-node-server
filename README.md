1. sudo npm install
2. sudo killall mongod
3. mongod
4. npm run dev

input: in "Post man" send POST request to localhost:3090/signup address
output: { "success": "true" }

input: in "Post man" send POST request with object { "email": "check1@mail.com", "password": "123" }
output: { "success": "true" }, try to print out stuff under console log
