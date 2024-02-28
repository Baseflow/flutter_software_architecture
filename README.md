# The Baseflow Application Architecture for Flutter application.

The goal of this repository is to describe Baseflow's ideal architecture of 
Flutter applications through documentation and working examples.

## Documentation

The documentation lives in the [./docs](./docs) folder and consists out of 
Markdown files which are automatically converted into static HTML using
[Docsify][1].

To locally work with [Docsify][1], which is useful for previewing changes
locally before publishing them to GitHub, install the docsify-cli tooling using
NPM:
```shell
npm install -g docsify-cli
```

To preview to documentation locally run the local server with `docsify serve` 
in the root of the repository:
```shell
docsify serve docs
```
Preview the site in a browser using the address: http://localhost:3000.

For more information on [Docsify][1] checkout their [documentation page][2]. 

[1]: https://docsify.js.org
[2]: https://docsify.js.org/#/?id=docsify
