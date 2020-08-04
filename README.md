# Node.js & Passport Login

This is a user login and registration app using Node.js, Express, Passport, Mongoose, EJS and some other packages.

### Version: 2.0.0

### Usage

```sh
$ npm install
```

```sh
$ npm start
# Or run with Nodemon
$ npm run dev

# Visit http://localhost:5000
```

### MongoDB

Add "config/keys.js" and add your MongoDB URI, local or Atlas
dbPassword = 'mongodb+srv://<username>:<pass>@cluster0.udpgg.mongodb.net/test'

module.exports = {
    mongoURI: dbPassword
};

