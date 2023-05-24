# Chat-Web-App

## Template

> 1.  https://www.youtube.com/watch?v=otaQKODEUFs&ab_channel=KishanSheth
> 2.  https://github.com/koolkishan/chat-app-react-nodejs

## React + Node.js

> 1.  Node.js

```javascript
    "bcrypt": "^5.0.1",
    "cors": "^2.8.5",
    "dotenv": "^16.0.0",
    "express": "^4.17.2",
    "jsonwebtoken": "^9.0.0",
    "mongoose": "^6.2.1",
    "nodemon": "^2.0.15",
    "socket.io": "^4.4.1"
```

> 2.  React.js

```javascript
    "@testing-library/jest-dom": "^5.16.2",
    "@testing-library/react": "^12.1.2",
    "@testing-library/user-event": "^13.5.0",
    "axios": "^0.25.0",
    "buffer": "^6.0.3",
    "emoji-picker-react": "^3.5.1",
    "react": "^17.0.2",
    "react-dom": "^17.0.2",
    "react-icons": "^4.3.1",
    "react-router-dom": "^6.2.1",
    "react-scripts": "5.0.0",
    "react-toastify": "^8.1.1",
    "socket.io-client": "^4.4.1",
    "styled-components": "^5.3.3",
    "uuid": "^8.3.2",
    "web-vitals": "^2.1.4"
```

## Install node_modules

    > npm i

## Postman for Node.js - jsonwebtoken

> 1.  You can register in the route
>     http://localhost:5000/api/auth/register

Use this creadentials

```json
{
  "email": "test@test.com",
  "username": "test",
  "password": "testtest"
}
```

> 2.  Late, login in the route and copy the token after login
>     http://localhost:5000/api/auth/login

```json
{
  "username": "test",
  "password": "testtest"
}
```

> 3.  In postman Headers add "auth-token" and in Value add the token.
>     Now you can use this route http://localhost:5000/api/auth/allusers/{\_id} The id is the id of a mongo object \_id
