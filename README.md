# CEA Documentation

[![Build Status](https://travis-ci.org/ut-cea/docs.svg?branch=master)](
    https://travis-ci.org/ut-cea/docs)

Contains various documentation for CEA members to get going with programming!
Created with [GitBook](https://github.com/GitbookIO/gitbook).

[Read it here!](https://ut-cea.github.io/docs/)

## Building from Source

### Prerequisites

- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [Node.js and npm](https://nodejs.org/en/) (A version over Node.js 6 should be
    fine)

### Getting the Repo and Installing

```
$ git clone https://github.com/ut-cea/docs.git ut-cea-docs
$ cd ut-cea-docs
$ npm install
```

This will get the repo and then install any needed npm and gitbook-cli
dependencies.

### Building the GitBook

```
$ npm run build
```

This will build the GitBook inside a `_book/` directory. `_book/index.html` is
the main page for the docs.

### Hosting the Book Locally

```
$ npm run serve
```

This builds the source and hosts a server as well (on something like
http://localhost:4000/).
