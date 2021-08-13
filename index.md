---
title: Siren.js
---

Siren.js provides tools for working with [Siren]. Unsurprisingly, our target is
JavaScript, but some of the tools may be helpful to other users as well.

[siren]: https://github.com/kevinswiber/siren

## Core

The [`@siren-js/core`](https://siren-js.github.io/core) package provides the
core functionality for Siren.js; namely, generating and parsing Siren
representations.

## Client

[`@siren-js/client`](https://siren-js.github.io/client) is our bread-and-butter
library for Siren API clients. It handles all the protocol semantics of
communicating with a Siren API server (following links, submitting actions,
etc.), supporting many of our [specification extensions][ext].

[ext]: #specification-extensions

## SireNg

[SireNg](https://github.com/siren-js/ng) is Siren.js for Angular users.
Primarily used for building dynamic forms backed by Siren actions. Published as
[`@siren-js/ng`](https://github.com/siren-js/ng/tree/main/projects/siren-js/ng)
on NPM.

## API Browser

Our [API browser](https://siren-js-api-browser.herokuapp.com) can be used to
browse any Siren API. It's developed with [React] and [Bulma] and deployed on
[Heroku]. It uses our [client](#client) and supports several of our
[specification extensions][ext].

[bulma]: https://bulma.io/documentation
[heroku]: https://heroku.com
[react]: https://reactjs.org

## Specification Extensions

We define several [extensions](https://siren-js.github.io/spec-extensions) to
the Siren specification, agnostic of Siren.js and JavaScript. Many of the
extensions are simply detailed explanations of things (that may be obvious)
from the base specification, but they are intended to remove ambiguity and avoid
confusion.

## Examples

The [examples](https://github.com/siren-js/examples) repository contains demo
clients and servers utilizing Siren.js. Feel free to contribute your own
examples or add a link to your project that uses Siren.js!
