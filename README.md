This example demonstrates how to use [Express](http://expressjs.com/) 4.x and
[Passport](http://passportjs.org/) to authenticate users using Snapchat.  Use
this example as a starting point for your own web applications.

## Instructions

To install this example on your computer, clone the repository and install
dependencies.

```bash
$ git clone https://github.com/Snapchat/express-4.x-passport-snapchat-example.git
$ cd express-4.x-passport-snapchat-example
$ npm install
```

The example uses environment variables to configure the consumer key and
consumer secret needed to access snapchat's API.  Start the server with those
variables set to the appropriate credentials.

```bash
$ CLIENT_ID=__snapchat_CLIENT_ID__ CLIENT_SECRET=__snapchat_CLIENT_SECRET__ SESSION_SECRET=whatever node server.js
```

Open a web browser and navigate to [http://localhost:3000/](http://localhost:3000/)
to see the example in action.
