# About
This is a toy project for studying REACT and Node.js.

# Initiate
React : npm start
Node.js node ./server/server.js

# Tips
1. Execute both front and back at once

1) install run-all package
-> npm install npm-run-all --save

2) modify package.json
"scripts": {
    "start": "npm-run-all --parallel start:**",
    "start:client": "react-scripts start",
    "start:server": "node ./server/server.js",
}