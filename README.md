1. sudo npm install
2. create config.js in the root of application and export secret with any data: module.exports = { secret: 'sometext' }
3. sudo killall mongod
4. mongod
5. npm run dev

1. input: in "Post man" send POST request with valid data to localhost:3090/signup address
2. then copy token's value from output
3. choice GET request for localhost:3000
4. go to headers section and add 'authorization' key with value of copied token
output: object: { "hi": "there" }

