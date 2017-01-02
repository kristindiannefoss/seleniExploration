# seleniExploration
testcafe vs selenium



## Run the Server

To see your code in action, you need to fire up a development server. Use the command:

```shell
npm start
```

Once the server is running, visit in your browser:

* `http://localhost:8080/webpack-dev-server/` to run your application.
* `http://localhost:8080/webpack-dev-server/test.html` to run your test suite in the browser.

To build the static files:

```js
npm run build
```

## Run Tests in the Terminal

To run all of your tests:

```js
npm test
```

## File Organization

Webpack is somewhat opinionated about how files are organized. Here is a brief guide on how to organize development and test files.

### Development Files

Node and webpack work together to help us organize our files and keep responsibilities separated.

More on this coming soon...

### Test Files

Near the end of game time, you will have multiple objects for your game that are tested separately with individual test files. The `/test/index.js` file serves as an "entry point" for mocha to load all of the tests you write.

More on this coming soon...
