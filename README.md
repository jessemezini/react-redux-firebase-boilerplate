# React, Redux Firebase Boilerplate

> [Firebase](https://www.firebase.com) is a powerful platform for your mobile and web applications that lets you build apps fast without managing servers. Firebase gives you the tools and infrastructure to build better apps and grow successful businesses.

> [React](https://www.firebase.com) A javascript library for building user interfaces

> [Redux](http://redux.js.org/) Redux is a predictable state container for JavaScript apps.

### Boilerplate Introduction
Boilerplate is designed for quickly spin up your apps with Firebase, using bunch of awesome new front-end technologies includes webpack build system, hot reloading, routing & sass support.

## Features
* [react](https://github.com/facebook/react)
* [redux](https://github.com/rackt/redux)
* [firebase](https://www.npmjs.com/package/firebase)
* [react-router](https://github.com/rackt/react-router)
* [redux-promise](https://github.com/acdlite/redux-promise)
* [webpack](https://github.com/webpack/webpack)
* [babel](https://github.com/babel/babel)

Quick Start
-----------

```shell
$ git clone https://github.com/btomashvili/react-redux-firebase-boilerplate.git
$ cd react-redux-firebase-boilerplate
$ npm install
$ npm run dev
```

Firebase settings
--------
First you need to create your firebase application to fetch settings for boilerplate. For more information how to add your web app check this [resource](https://firebase.google.com/docs/web/setup). After it copy your settings from firebase and fill config.js

```javascript
module.exports = {

    FIREBASE_CONFIG: {

      apiKey: "",
      authDomain: "",
      databaseURL: "",
      storageBucket: "",

    }
}
```

Commands
--------

|Script|Description|
|---|---|
|`npm run dev`| Run development server with webpack-dev-server @ `localhost:3000`|
|`npm run build`| Test, and build the application to `./dist`|
|`npm start`| Start production ready app with pm2 from `./dist` @ `localhost:8080`|


![screen](https://dl.dropboxusercontent.com/content_link/WH3JGMUchuaRXCl7L8BsMsDrL221vMYmODRk5LYSt6WS0R9cMVvRT73wxLqYWIwf/file "react_redux_firebase_boilerplate")
