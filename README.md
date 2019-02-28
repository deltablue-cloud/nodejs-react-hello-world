# Simple Universal React.js "Hello world" Application


In this repository you can find an example of a very simple starting point for using universal/isomorphic/shared React.js +
Node.js + Express.js.

This is part of a tutorial explaining how to deploy and run a NodeJS application on DeltaBlue.
More information can be found on https://delta.blue/blog/deploy-run-nodejs-application-tutorial

We based this on the existing Git repo from Vance Lucas: https://github.com/vlucas/universal-react-helloworld

# Installation

Use Git to clone this app, then:


```
npm ci
```

or 

```
npm install
```

# Commands

Start the server with all the code transpiled and bundled in a single command:

```
npm run start
```

Transpile all the ES6/ES2015 JavaScript to ES5 for Node and browsers

```
npm run build
```

Bundle all the client-side JavaScript into a single file (`public/js/bundle.js`)

```
npm run bundle
```

