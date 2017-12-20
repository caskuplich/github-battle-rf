# GitHub Battle

> Example app developed in the [React Fundamentals
course](https://tylermcginnis.com/courses/react-fundamentals/).

In GitHub Battle you enter two GitHub usernames and it will declare a winner.

## Running on local machine

You need [Node.js](https://nodejs.org/) installed in your system to run the app.
After cloning the repository, at the project root directory, run the following
commands in a terminal:

```bash
$ npm install # install dependencies
$ npm start   # start the development server
```

The app will be running at http://localhost:8080/. Point your browser to this
URL if it doesn't open automatically.

## Deploying to Firebase

### Setup a Firebase project

You will need a [Firebase account](https://firebase.google.com/). Create a new
Firebase project and run the following command in a terminal:

```bash
$ npm run firebase-init # setup a new firebase project
```

Enter your login credentials if you aren't logged in yet and select the name of
your new Firebase project.

The other questions should be answered as following:

```
? What do you want to use as your public directory? dist
? Configure as a single-page app (rewrite all urls to /index.html)? Yes
? File dist/index.html already exists. Overwrite? No
```

### Deploy

To deploy the project to Firebase, just run the following command:

```bash
$ npm run deploy
```

The project will be built and deployed on the Firebase project you selected in
the setup.
