# my-html5-boilerplate

My html5 boilerplate with configuration and capabilities for starting typescript-based esnext apps or moduless

## Contains

* **TypeScript** compilation and ``.d.ts`` definition generation.
* **Jest**. A modern, well integrated test framework with optional Typescript support (provided through **ts-jest**) and coverage reporting.

## In Development

Easily serve the contents with a local HTTP2 server [simplehttp2server](https://github.com/GoogleChrome/simplehttp2server) from the Google Chrome team:

On first run will drop ``cert.perm`` and ``key.perm`` into directory being served

## Setup

```
$ npm install
```

## Development

```
$ npm build
$ cd src
$ simplehttp2server
```

## Testing

```
npm test
```

## Note

This project is still evolving to encompass further refinements and customizations.

### To Do

### License

[MIT](LICENSE.md)
