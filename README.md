# Dust.js [![Build Status](https://travis-ci.org/netshoes/dustjs.svg?branch=master)](https://travis-ci.org/netshoes/dustjs) [![Coverage Status](https://coveralls.io/repos/github/netshoes/dustjs/badge.svg?branch=master)](https://coveralls.io/github/netshoes/dustjs?branch=master)

Asynchronous Javascript templating for the browser and server. This fork is maintained by [LinkedIn](http://linkedin.github.io/).

## Install

### NPM

**Important**: We recommend that you lock your version of Dust to a specific minor version, instead of a major version. By default, NPM will add `"dustjs-linkedin": "^2.x.y"` to your package.json, which will install new minor versions automatically.

    npm install --save --production dustjs-linkedin
    # If you want the dustc compiler available globally
    npm install --global --production dustjs-linkedin

If you want to add the [Dust helpers](https://github.com/linkedin/dustjs-helpers) or [secure filters](https://github.com/linkedin/dustjs-filters-secure):

    npm install --save --production dustjs-helpers
    npm install --save --production dustjs-filters-secure

### Bower

    bower install --save dustjs-linkedin

## Get Started

* Read [dustjs.com](http://www.dustjs.com/) for guides, tutorials, and documentation.
* Check out the `examples/` directory in the repo for simple examples to help you get started using Dust in a variety of ways.

## Flavor changes

* Delayed Chunk API - Setting a Chunk to be rendered latest on Rendering phase.
* Not related to promises
* Non-compatible with Stream (yet).
* Check [unit tests](https://github.com/netshoes/dustjs/blob/master/test/templates/all.js#L2608) to see it working.

## Contribute

* The team provides support on [Stack Overflow](https://stackoverflow.com/questions/tagged/dust.js), so that's the best place to ask questions.
* Bug or feature? We welcome issues and pull requests! If you'd like to submit a PR, check out the guide to [contributing](https://github.com/linkedin/dustjs/wiki/Contributing). PRs should include unit tests.
