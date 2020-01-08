# dart2js-module-poc

This is a POC of writing modules in `dart`, then import and to be used in `JavaScript`.

The `lib/dart_sdk.js` and `lib/dart_sdk.js.map` files are extracted from [`dart_sdk`](https://dart.dev/tools/sdk).

## Prerequisite

Install `dart-sdk` and `node` on your machine.

## Getting started

- Use `yarn build-dart` to build `dart` module to `JavaScript`
- Use `yarn build` to build `JavaScript` code
- Serve the files in `/dist` folder by any http server (e.g. [http-server](https://www.npmjs.com/package/http-server))
- Open the web in browser and watch the console output.
