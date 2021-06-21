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
`@siren-js/ng` on NPM.

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
the Siren specification. Many of the extensions are simply detailed explanations
of things that are likely obvious from the base specification, but they
(hopefully) remove ambiguity and avoid confusion.

## Examples

The [examples](https://github.com/siren-js/examples) repository is for (you
guessed it!) Siren.js examples. This is currently empty 😔, so feel free to
contribute if you want to show off an API.
