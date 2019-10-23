## Basic installation
```json
{
  "name": "my-app",
  "version": "1.0.0",
  "description": "",
  "main": "src/server.js",
  "scripts": {
    "start": "nodemon --exec babel-node src/server.js",
    "build": "babel src --out-dir dist",
    "serve": "node dist/server.js"
  },
  "author": "",
  "license": "ISC",
  "dependencies": {
  },
  "devDependencies": {
    "@babel/cli": "^7.0.0-rc.1",
    "@babel/core": "^7.0.0-rc.1",
    "@babel/node": "^7.0.0-rc.1",
    "@babel/preset-env": "^7.0.0-rc.1",
    "nodemon": "^1.18.3"
  }
}
```
