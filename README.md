# generator-fluxible

[![npm version](https://badge.fury.io/js/generator-fluxible.svg)](http://badge.fury.io/js/generator-fluxible)
[![Build Status](https://travis-ci.org/yahoo/generator-fluxible.svg?branch=master)](https://travis-ci.org/yahoo/generator-fluxible)
[![Dependency Status](https://david-dm.org/yahoo/generator-fluxible.svg)](https://david-dm.org/yahoo/generator-fluxible)
[![devDependency Status](https://david-dm.org/yahoo/generator-fluxible/dev-status.svg)](https://david-dm.org/yahoo/generator-fluxible#info=devDependencies)

## Getting Started

```bash
npm install -g yo
```

To install generator-fluxible from npm, run:

```bash
npm install -g generator-fluxible
```

Finally, initiate the generator:

```bash
yo fluxible
```

Then run `gulp` or `grunt`, depending on your choice. Browse to `http://localhost:3000` to see a very simple Fluxible site with server-side rendering and client-side navigation.

## Debugging

Fluxible uses [debug](https://www.npmjs.com/package/debug) to expose debugging information on the server and client. 

### Server

Start the application with the `DEBUG` environment variable: `DEBUG=* grunt`.

### Client

`fluxibleDebug` is exposed to the `window` object to manage debugging. You can enable it via the browser console: `fluxibleDebug.enable('*');` then refresh the page. To disable, type the following: `fluxibleDebug.disable();`.
