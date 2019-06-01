# ![CF](http://i.imgur.com/7v5ASc8.png) LAB

## lab-13-bearer-auth

### Author: Bonnie Wang

### Links and Resources

- [submission PR](http://xyz.com)
- [travis](http://xyz.com)

### Modules

#### `middleware.js`

##### authenticate user/token

#### `router.js -> router`

#### `users-model.js -> generate key/token, compare passwords`

#### `google.js -> google OAuth`

### Setup

#### `.env` requirements

- `PORT` - Port Number
- `MONGODB_URI` - URL to the running mongo instance/db

#### Running the app

- `npm i`
- `npm start`
- Endpoint: `/singin/`
  - sings in user.
- Endpoint: `/oauth/`
  - verify user
- Endpoint: `/protected-route/`
  - viewable to verified users
