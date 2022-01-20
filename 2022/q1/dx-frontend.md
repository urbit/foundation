# Improve the front-end developer experience

[Back](/../../#Q1)

**Owner:** `~tinnus-napbus`

Developers should be able to learn full-stack Urbit development by completing
Hoon School, the Gall Guide and a new front-end integration guide. It should
also be possible for front-end developers to get started without learning any
Hoon.

## Problems

- While some aspects of front-end integration are documented in various places,
  there is not a comprehensive tutorial.
- JS libraries like http-api are not documented.
- Existing front-end integration docs like those for Eyre are oriented towards
  hoon devs, not JS devs. This makes it difficult for front-end devs who want
  to integrate with existing agents but don't want to learn full-stack Urbit
  development.
- Most agents are undocumented and require knowing hoon and reading their
  source to figure out their interfaces.

## Plan

- Add a front-end integration guide which follows on from the Gall guide.
  This will cover mark conversions, JSON, Eyre, http-api and best practices.
  This will be oriented towards devs who have gone through Hoon School and the
  Gall Guide, who want to learn full-stack urbit development. This will walk
  through building an example To-Do app, front-end and back-end.
- Document the http-api library.
- Write a succinct guide to Eyre & agent communications oriented towards JS
  devs who don't know hoon.
- Document core Gall agents that front-end devs might wish to integrate with,
  and provide JSON examples of their types, pokes, etc. This will be done in
  the [%docs app](dx-agent-docs.md).
