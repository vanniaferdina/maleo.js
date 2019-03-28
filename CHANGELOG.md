# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## 0.0.15 (2019-03-27)


### Bug Fixes

* **babelconfigjs:** fix built absolute path to relative path ([#19](https://github.com/airyrooms/maleo.js/issues/19)) ([064352c](https://github.com/airyrooms/maleo.js/commit/064352c))
* **circleci:** add build workflow ([c56f528](https://github.com/airyrooms/maleo.js/commit/c56f528))
* **css-plugin:** first render isl not working ([#48](https://github.com/airyrooms/maleo.js/issues/48)) ([7e67643](https://github.com/airyrooms/maleo.js/commit/7e67643))
* **development:** fix tslint exclude node_modules [skip ci] ([#155](https://github.com/airyrooms/maleo.js/issues/155)) ([68b121a](https://github.com/airyrooms/maleo.js/commit/68b121a))
* **getinitialprops:** fix get initial props ([#133](https://github.com/airyrooms/maleo.js/issues/133)) [skip ci] ([98c65c7](https://github.com/airyrooms/maleo.js/commit/98c65c7)), closes [#131](https://github.com/airyrooms/maleo.js/issues/131)
* **maleo-core:** fix webpack undefined ([#150](https://github.com/airyrooms/maleo.js/issues/150)) [skip ci] ([c6467c1](https://github.com/airyrooms/maleo.js/commit/c6467c1)), closes [#149](https://github.com/airyrooms/maleo.js/issues/149)
* **maleo-plugins:** fix redux-plugins to follow csp standards noscript ([#147](https://github.com/airyrooms/maleo.js/issues/147)) ([b2b7004](https://github.com/airyrooms/maleo.js/commit/b2b7004)), closes [#49](https://github.com/airyrooms/maleo.js/issues/49)
* **require cache hmr:** add nextjs license ([#40](https://github.com/airyrooms/maleo.js/issues/40)) ([e5d0cc9](https://github.com/airyrooms/maleo.js/commit/e5d0cc9))
* **ssr:** fix component getinitialprops ([#127](https://github.com/airyrooms/maleo.js/issues/127)) ([91f7257](https://github.com/airyrooms/maleo.js/commit/91f7257))
* **webpack:** fix get static entries wront custom entries [skip ci ]([#160](https://github.com/airyrooms/maleo.js/issues/160)) ([6c073fb](https://github.com/airyrooms/maleo.js/commit/6c073fb))
* **webpack:** missing .js extension on filename ([#30](https://github.com/airyrooms/maleo.js/issues/30)) ([159e30a](https://github.com/airyrooms/maleo.js/commit/159e30a))
* **webpack client server:** remove hmr but fix sync ([#33](https://github.com/airyrooms/maleo.js/issues/33)) ([8a9f326](https://github.com/airyrooms/maleo.js/commit/8a9f326))
* **webpack stats-writer plugin:** add dynamic key on stats json ([#41](https://github.com/airyrooms/maleo.js/issues/41)) ([114c465](https://github.com/airyrooms/maleo.js/commit/114c465))


### Features

* **maleo playground:** add default server and client ([#29](https://github.com/airyrooms/maleo.js/issues/29)) ([e40897b](https://github.com/airyrooms/maleo.js/commit/e40897b))
* **maleo webpack:** add rimraf before run and cache server ([#35](https://github.com/airyrooms/maleo.js/issues/35)) ([3b45e4e](https://github.com/airyrooms/maleo.js/commit/3b45e4e))
* **maleo-core:** use noscript for initial data ([#146](https://github.com/airyrooms/maleo.js/issues/146)) ([d84545e](https://github.com/airyrooms/maleo.js/commit/d84545e)), closes [#49](https://github.com/airyrooms/maleo.js/issues/49)
* **maleo-plugin:** improve maleo plugin [skip ci] ([#154](https://github.com/airyrooms/maleo.js/issues/154)) ([10638c5](https://github.com/airyrooms/maleo.js/commit/10638c5)), closes [#152](https://github.com/airyrooms/maleo.js/issues/152)
* **maleo-routes-split:** auto add key for routes ([#42](https://github.com/airyrooms/maleo.js/issues/42)) ([7a61301](https://github.com/airyrooms/maleo.js/commit/7a61301))
* **webpack:** change maleo-routes.json to routes.json ([#74](https://github.com/airyrooms/maleo.js/issues/74)) ([b3b9e2f](https://github.com/airyrooms/maleo.js/commit/b3b9e2f))
* **webpack client preset:** add simple hmr refresh ([#37](https://github.com/airyrooms/maleo.js/issues/37)) ([61fc321](https://github.com/airyrooms/maleo.js/commit/61fc321))
* **webpack loaders routes:** add auto code splitting on routes ([#36](https://github.com/airyrooms/maleo.js/issues/36)) ([a80c4e9](https://github.com/airyrooms/maleo.js/commit/a80c4e9))


### BREAKING CHANGES

* **webpack client preset:** new hash is not synced
* **maleo playground:** client haven't use the route yet

feat(client route): add register route

added register route for client to be able to pass it to window and feed to default client

docs(readmemd): update docs for default server and client

feat(webpack client wrap): add register wrap to window

feat(webpack register-loader client): auto register

add auto register using register loader for wrap and routes to be used by client

feat(webpack app client): add auto register for app

refactor(webpack): clean up static entries

refactor static entries to be more readable

fix(webpack): comment out hardsourcewbp

fix(webpack): fix node externals

fix(webpack server tsplugin): fix error not bundling on client

error caused by webpack getting imported to server.ts not sure what cause the error

feat(client): added register entry class

docs(readmemd): update register route readme