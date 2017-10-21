![awesome koa](https://github.frapsoft.com/top/awesome-koa.jpg)

# Awesome Koa [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Javascript](https://badges.frapsoft.com/javascript/code/javascript.svg?v=100)](https://github.com/ellerbrock/javascript-badges/) [![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=102)](https://github.com/ellerbrock/open-source-badges/) [![Gitter Chat](https://badges.gitter.im/frapsoft/frapsoft.svg)](https://gitter.im/frapsoft/frapsoft/)

> Useful resources for creating apps and working with [Koa](http://koajs.com) 

  - [Links](#links)
  - [Examples & Boilerplates](#examples--boilerplates)
  - [Middleware](#middleware)
  - [Others](#others)
  - [Videos](#videos)

## Status

[![Deadlink Test](https://travis-ci.org/ellerbrock/awesome-koa.svg?branch=master)](https://travis-ci.org/ellerbrock/awesome-koa)

**Info:** Green Build Status means there should be no Deadlinks in this List.<br>
You can find the Testfiles on [travis-deadlink-scanner](https://github.com/ellerbrock/travis-deadlink-scanner).

## Links

- [Koa](https://github.com/koajs/koa) - Expressive middleware for node.js using generators
- [co](https://github.com/tj/co) - The ultimate generator based flow-control goodness for nodejs

## Examples & Boilerplates

- [api-boilerplate](https://github.com/koajs/api-boilerplate) - API application boilerplate
- [kick-off-koa](https://github.com/koajs/kick-off-koa) - An intro to koa via a set of self-guided workshops
- [workshop](https://github.com/koajs/workshop) - Koa Training Workshop
- [examples](https://github.com/koajs/examples) - Example Koa apps
- [babel-es6-es7-npm-skeleton](https://github.com/ellerbrock/babel-es6-es7-npm-skeleton) - Babel ES6 / ES7 - Testing, Benchmark, Auto Reload, Linting
- [K2](https://github.com/hongymagic/k2) - Koa2, Babel ES6/7, GraphQL, passport-local based authentication, PostgreSQL, Jest for Unit and Integration testing and more
- [koa-firebase](https://github.com/antonybudianto/koa-firebase) - Koa with Firebase middleware integration starter

  **Info:** Lots of the Examples and Boilerplattes are outdated.<br>
  Also some of the features not work straight out of the Box with the new Version.<br>
  I'm working on a Boilerplatte with all the cutting edge stuff and will publish it later on my [GitHub Account](https://github.com/ellerbrock).

## Middleware

- [accesslog](https://github.com/koajs/accesslog) - Middleware for common log format access logs
- [api-boilerplate](https://github.com/koajs/api-boilerplate) - API application boilerplate
- [atomic-session](https://github.com/koajs/atomic-session) - Atomic sessions for Koa
- [badgeboard](https://github.com/koajs/badgeboard)
- [basic-auth](https://github.com/koajs/basic-auth) - blanket basic auth middleware
- [body-parsers](https://github.com/koajs/body-parsers) - collection of koa body parsers
- [bodyparser](https://github.com/koajs/bodyparser) - a body parser for koa
- [bundle](https://github.com/koajs/bundle) - Generic asset pipeline with caching, etags, minification, gzipping and sourcemaps.
- [bunyan-logger](https://github.com/koajs/bunyan-logger) - Koa middleware for bunyan request logging
- [cash](https://github.com/koajs/cash) - HTTP response caching for Koa
- [charset](https://github.com/koajs/charset) - use iconv-lite to encode the body and set charset to content-type
- [cluster](https://github.com/koajs/cluster) - Koa clustering and error handling utility
- [compose](https://github.com/koajs/compose) - Middleware composition utility
- [compress](https://github.com/koajs/compress) - Compress middleware for koa
- [conditional-get](https://github.com/koajs/conditional-get) - Conditional GET middleware for koa
- [convert](https://github.com/koajs/convert) - Convert koa generator-based middleware to promise-based middleware
- [cors](https://github.com/koajs/cors) - Cross-Origin Resource Sharing(CORS) for koa
- [cross-cookies](https://github.com/koajs/cross-cookies) - Easily set cookies across subdomains
- [csrf](https://github.com/koajs/csrf) - CSRF tokens for koa
- [ctx-basic-auth](https://github.com/koajs/ctx-basic-auth) - Augments Koa with ctx.basicAuth
- [ctx-cache-control](https://github.com/koajs/ctx-cache-control) - Augment Koa with ctx.cacheControl(maxAge)
- [ctx-paginate](https://github.com/koajs/ctx-paginate) - Augments Koa with ctx.paginate
- [ejs](https://github.com/koajs/ejs) - a koa view render middleware, support all feature of ejs
- [error](https://github.com/koajs/error) - Error response middleware (text, json, html)
- [etag](https://github.com/koajs/etag) - ETag support for Koa responses
- [examples](https://github.com/koajs/examples) - Example Koa apps
- [favicon](https://github.com/koajs/favicon) - Koa middleware for serving a favicon
- [file-server](https://github.com/koajs/file-server) - file serving middleware for koa
- [generic-session](https://github.com/koajs/generic-session) - koa session store with memory, redis or others.
- [html-minifier](https://github.com/koajs/html-minifier) - minify HTML responses like some crazy guy
- [is-json](https://github.com/koajs/is-json) - check if a koa body should be interpreted as JSON
- [joi-router](https://github.com/koajs/joi-router) - Configurable, input and output validated routing for koa
- [json](https://github.com/koajs/json) - pretty-printed JSON response middleware
- [json-error](https://github.com/koajs/json-error) - Error handler for pure-JSON apps
- [json-filter](https://github.com/koajs/json-filter) - Middleware allowing the client to filter the response to only what they need, reducing the amount of traffic over the wire.
- [jwt](https://github.com/koajs/jwt) - Koa middleware for validating JSON Web Tokens
- [kick-off-koa](https://github.com/koajs/kick-off-koa) - An intro to koa via a set of self-guided workshops
- [koa](https://github.com/koajs/koa) - Expressive middleware for node.js using generators
- [koa-fresh](https://github.com/koajs/koa-fresh) - koa-fresh: HTTP response freshness testing middleware base on koa and node-fresh
- [koa-github](https://github.com/koajs/koa-github) - simple github auth middleware for koa
- [koa-lusca](https://github.com/koajs/koa-lusca) - koa version of lusca. Application security for koa.
- [koa-markdown](https://github.com/koajs/koa-markdown) - Auto convert markdown to html for koa. Inspired by connect-markdown
- [koa-range](https://github.com/koajs/koa-range) - range request implementation for koa, see <http://tools.ietf.org/html/rfc7233>
- [koa-redis](https://github.com/koajs/koa-redis) - koa session with redis
- [koa-roles](https://github.com/koajs/koa-roles) - koa version of Connect-Roles
- [koa-rt](https://github.com/koajs/koa-rt) - koa rt with microtime
- [koa-safe-jsonp](https://github.com/koajs/koa-safe-jsonp) - Safe jsonp plusins for koa.
- [koa.io](https://github.com/koajs/koa.io) - Realtime web framework combine koa and socket.io.
- [koala](https://github.com/koajs/koala) - [SEEKING MAINTAINER] An HTTP/2 and ES6 Module-ready Koa Suite
- [locales](https://github.com/koajs/locales) - koa locales, i18n solution for koa
- [logger](https://github.com/koajs/logger) - Development style logging middleware
- [maxrequests](https://github.com/koajs/maxrequests) - Limit max requests on each http keepalive connection.
- [middleware-hook](https://github.com/koajs/middleware-hook) - low-level hooks for your middleware
- [mock](https://github.com/koajs/mock) - Simple web page mock middleware
- [mount](https://github.com/koajs/mount) - Mount other Koa applications or middleware to a given pathname
- [onerror](https://github.com/koajs/onerror) - an error handler for koa, hack ctx.onerror
- [override-method](https://github.com/koajs/override-method) - method override utility for koa
- [parameter](https://github.com/koajs/parameter) - parameter validate middleware for koa, powered by parameter
- [path-match](https://github.com/koajs/path-match) - koa route middleware
- [qs](https://github.com/koajs/qs) - qs for koa, and use querystring more safely.
- [querystring-strict](https://github.com/koajs/querystring-strict) - THIS REPOSITORY IS NOW DEPRECATED
- [ratelimit](https://github.com/koajs/ratelimit) - Rate limiter middleware
- [react-view](https://github.com/koajs/react-view) - A Koa view engine which renders React components on server
- [redis-session-sets](https://github.com/koajs/redis-session-sets) - Koa Redis sessions with field-referencing cross sets
- [resourcer](https://github.com/koajs/resourcer) - A simple resource directory mounter for koa.
- [resourcer-docs](https://github.com/koajs/resourcer-docs) - Simple app that generates documentation for routes mounted using koa-resourcer.
- [response-time](https://github.com/koajs/response-time) - X-Response-Time middleware
- [rewrite](https://github.com/koajs/rewrite) - URL rewriting middleware
- [route](https://github.com/koajs/route) - Simple route middleware
- [s3-cache](https://github.com/koajs/s3-cache) - Koa middleware to cache and serve from S3
- [send](https://github.com/koajs/send) - Transfer static files
- [sendfile](https://github.com/koajs/sendfile) - basic file-sending utility for koa
- [session](https://github.com/koajs/session) - Simple cookie-based session middleware
- [snapshot](https://github.com/koajs/snapshot) - take snapshot when request, cache by request path.
- [stateless-csrf](https://github.com/koajs/stateless-csrf) - CSRF without sessions.
- [static](https://github.com/koajs/static) - Static file server middleware
- [static-cache](https://github.com/koajs/static-cache) - Static cache for koa
- [statsd](https://github.com/koajs/statsd) - Statsd middleware
- [timer](https://github.com/koajs/timer) - time your middleware
- [todo](https://github.com/koajs/todo) - a todo example write with koa and react
- [trace](https://github.com/koajs/trace) - generic tracing for koa
- [trace-influxdb](https://github.com/koajs/trace-influxdb) - InfluxDB tracing for koa-trace
- [trie-router](https://github.com/koajs/trie-router) - Trie-routing for Koa
- [userauth](https://github.com/koajs/userauth) - koa user auth middleware
- [workshop](https://github.com/koajs/workshop) - Koa Training Workshop

## Generators

- [Generators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Generator) - Mozilla Developer Network (MDN)

## Videos

- [KnowThen](http://knowthen.com/category/node-js/) - Videos about Koa and Generators
- [Generators in JavaScript](https://youtu.be/ategZqxHkz4) - What, Why and How

## Other Web Development Lists

- [Atom for Web Developer](https://github.com/ellerbrock/atom-for-webdeveloper) - Useful Packages and Configuration for a better Workflow
- [Node.js for Web Developers](https://github.com/ellerbrock/nodejs-for-webdeveloper) - Full Stack Javascript Development with Node.js
- [Chrome Extensions for Web Developer](https://github.com/ellerbrock/chrome-extensions-for-webdeveloper) - A list with useful Chrome Extensions
- [Publishing NPM Packages for Developers](https://github.com/ellerbrock/publishing-npm-packages) - Introduction how to write and publish npm Modules.
- [Awesome Typescript](https://github.com/ellerbrock/awesome-typescript) - A collection of awesome TypeScript resources.
- [Docker Tutorial](https://github.com/ellerbrock/docker-tutorial) - Getting Started with Docker.
- [Fish Shell Setup OS X](https://github.com/ellerbrock/fish-shell-setup-osx) - Terminal Setup for OS X with Fish Shell, Fisherman, Powerline Fonts and iTerm2.

### Contact / Social Media

_Get the latest News about Web Development, Open Source, Tooling, Server & Security_

[![Twitter](https://github.frapsoft.com/social/twitter.png)](https://twitter.com/frapsoft/)[![Facebook](https://github.frapsoft.com/social/facebook.png)](https://www.facebook.com/frapsoft/)[![Google+](https://github.frapsoft.com/social/google-plus.png)](https://plus.google.com/116540931335841862774)[![Gitter](https://github.frapsoft.com/social/gitter.png)](https://gitter.im/frapsoft/frapsoft/)[![Github](https://github.frapsoft.com/social/github.png)](https://github.com/ellerbrock/)

### Development by

Developer / Author: [Maik Ellerbrock](https://github.com/ellerbrock/)<br>
Company: [Frapsoft](https://github.com/frapsoft/)

### License

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)<br>

This work by [Maik Ellerbrock](https://github.com/ellerbrock/) is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
