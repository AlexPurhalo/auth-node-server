1. sudo npm install
2. create config.js in the root of application and export secret with any data: module.exports = { secret: 'sometext' }
3. sudo killall mongod
4. mongod
5. npm run dev

input: in "Post man" send POST request with valid data to localhost:3090/signup address
output: object with 'token' key that contains string with different char, dig, and sym as value

