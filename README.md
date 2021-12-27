
*THIS APP IS STILL IN DEVELOPMENT*

Take-Over is a Full MERN Stack web application using redux. 

## Technologies

- [React](https://reactjs.org): Front-end library for building UIs
- [React Router](https://reacttraining.com/react-router/): a standard library for routing in React.
- [Express](http://expressjs.com/): Back-end framework for building APIs
- [Node](https://nodejs.org/en/): Back-end JavaScript runtime engine
- [MongoDB](https://www.mongodb.com/): NoSQL database
- [Mongoose](https://mongoosejs.com/): MongoDB object modeling tool designed to work in an asynchronous environment
- [Redux](https://redux.js.org/basics/usagewithreact): State management between React components
- [Babel](https://babeljs.io/): Transpiler to convert ECMAScript 2015+ code into a backwards compatible version of JavaScript in current and older browsers or environments


## Configuration

Be sure you connect to Mongodb & add your `MONGOURI` into `config/keys.js`.

```javascript
module.exports = {
  mongoURI: "MONGODB_atlas_URI",
  secretOrKey: "secret"
};
```

## Quick Start

```javascript
// Install dependencies for server & client
npm install && npm run client-install

// Run client & server with concurrently
npm run dev

// Server runs on http://localhost:5000 and client on http://localhost:3000
```

For deploying to Heroku, please refer to [this](https://www.youtube.com/watch?v=71wSzpLyW9k) helpful video by TraversyMedia.
