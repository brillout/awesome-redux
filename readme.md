## Awesome Redux [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Curated List of Redux Libraries / Tools.

###### Learning Material

I recommend the excellent learning material at http://redux.js.org/.

###### Contribution

To add a Library / Tool:

  - Add a line to this list by creating a new pull request
  - Line format: ` - [npm-package-name](https://github.com/foo/bar) - Description without emojis.`
  - Add the line at the end of a section
  - If it doesn't fit any section then open a new issue so we can discuss creating a new section

###### Collaboration

I'm looking to maintain this list with others. Let me know if you are interested. We would then create a GitHub organization.


#### Table of Content
- [Code Architecture](#code-architecture)
- [Utilities](#utilities)
- [Code Style](#code-style)
- [Dev Tools / Inspect](#dev-tools--inspect)
- [React Integration](#react-integration)
- [Other Integrations](#other-integrations)
- [Stack Ensembles / Starter Kits / Generators / Boilerplates](#stack-ensembles--starter-kits--generators--boilerplates)
- [Miscellaneous](#miscellaneous)


<br/>
---


# Code Architecture

*Aims to improve the overall structure of the source code. Makes reasoning about the code easier.*

 - [redux-schema](https://github.com/ddsol/redux-schema) - Automatic actions, reducers and validation for Redux.
 - [redux-tcomb](https://github.com/gcanti/redux-tcomb) - Immutable and type-checked state and actions for Redux.
 - [redux-action-tree](https://github.com/cerebral/redux-action-tree) - The Cerebral signals running with Redux.
 - [redux-elm](https://github.com/salsita/redux-elm) - The Elm Architecture in JavaScript.


# Utilities

 - [redux-orm](https://github.com/tommikaikkonen/redux-orm) - A small, simple and immutable ORM to manage relational data in your Redux store.
 - [redux-api-middleware](https://github.com/agraboso/redux-api-middleware) - Redux middleware for calling an API.
 - [redux-ignore](https://github.com/omnidan/redux-ignore) - Higher-order reducer to ignore redux actions.
 - [redux-modifiers](https://github.com/calvinfroedge/redux-modifiers) - A collection of generic functions for writing redux reducers to operate on various data structures.
 - [rereduce](https://github.com/slorber/rereduce) - Reducer library for Redux.
 - [redux-search](https://github.com/treasure-data/redux-search) - Redux bindings for client-side search.
 - [redux-logger](https://github.com/evgenyrodionov/redux-logger) - Logger middleware for redux.
 - [redux-immutable](https://github.com/gajus/redux-immutable) - Redux-immutable is used to create an equivalent function of Redux combineReducers that works with Immutable.js state.
 - [reselect](https://github.com/reactjs/reselect) - Selector library for Redux.
 - [redux-requests](https://github.com/idolize/redux-requests) - Manages in-flight requests with a Redux reducer to avoid issuing duplicate requests.
 - [redux-undo](https://github.com/omnidan/redux-undo) - Higher order reducer to add undo/redo functionality to redux state containers.


###### Store Persistence

 - [redux-storage](https://github.com/michaelcontento/redux-storage) - Persistence layer for redux with flexible backends.
 - [redux-persist](https://github.com/rt2zz/redux-persist) - Persist and rehydrate a redux store.


###### Asynchronous Actions / Side Effects

 - [redux-saga](https://github.com/yelouafi/redux-saga) - An alternative side effect model for Redux apps.
 - [redux-promise-middleware](https://github.com/pburtchaell/redux-promise-middleware) - Redux middleware for resolving and rejecting promises with conditional optimistic updates.
 - [redux-effects](https://github.com/redux-effects/redux-effects) - You write pure functions, redux-effects handles the rest.
 - [redux-thunk](https://github.com/gaearon/redux-thunk) - Thunk middleware for Redux.
 - [redux-connect](https://github.com/makeomatic/redux-connect) - Provides decorator for resolving async props in react-router, extremely useful for handling server-side rendering in React.
 - [redux-loop](https://github.com/raisemarketplace/redux-loop) - A port of elm-effects and the Elm Architecture to Redux that allows you to sequence your effects naturally and purely by returning them from your reducers.
 - [redux-side-effects](https://github.com/salsita/redux-side-effects) - Redux toolset for keeping all the side effects inside your reducers while maintaining their purity.


# Code Style

*Aims to make parts of the source code easier to read and/or write.*

 - [redux-act](https://github.com/pauldijou/redux-act) - An opinionated lib to create actions and reducers for Redux.
 - [redux-crud](https://github.com/Versent/redux-crud) - A set of standard actions and reducers for Redux CRUD Applications.


# Dev Tools / Inspect

 - [redux-devtools-inspector](https://github.com/alexkuz/redux-devtools-inspector) - Another Redux DevTools Monitor.
 - [redux-diff-logger](https://github.com/fcomb/redux-diff-logger) - Diff logger between states for redux.
 - [redux-devtools-chart-monitor](https://github.com/romseguy/redux-devtools-chart-monitor) - A chart monitor for Redux DevTools.
 - [redux-devtools](https://github.com/gaearon/redux-devtools) - DevTools for Redux with hot reloading, action replay, and customizable UI.
 - [redux-devtools-dispatch](https://github.com/YoruNoHikage/redux-devtools-dispatch) - Dispatch your actions manually to test if your app reacts well.
 - [redux-devtools-dock-monitor](https://github.com/gaearon/redux-devtools-dock-monitor) - A resizable and movable dock for Redux DevTools monitors.
 - [redux-devtools-filterable-log-monitor](https://github.com/bvaughn/redux-devtools-filterable-log-monitor) - Filterable tree view monitor for Redux DevTools.
 - [redux-devtools-log-monitor](https://github.com/gaearon/redux-devtools-log-monitor) - The default monitor for Redux DevTools with a tree view.
 - [remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools) - Use Redux DevTools remotely for React Native, hybrid, desktop and server side Redux apps.


# React Integration

 - [redux-test-recorder](https://github.com/conorhastings/redux-test-recorder) - A redux middleware to automatically generate tests for reducers through ui interaction.
 - [react-redux](https://github.com/reactjs/react-redux) - Official React bindings for Redux.
 - [react-easy-universal](https://github.com/keystonejs/react-easy-universal) - Universal Routing &amp; Rendering with React &amp; Redux was too hard. Now it&#39;s easy.


###### Routing

 - [redux-async-connect](https://github.com/Rezonans/redux-async-connect) - It allows you to request async data, store them in redux state and connect them to your react component.
 - [redux-tiny-router](https://github.com/Agamennon/redux-tiny-router) - A Router made for Redux and made for universal apps! stop using the router as a controller... its just state!.
 - [redux-router](https://github.com/acdlite/redux-router) - Redux bindings for React Router &ndash; keep your router state inside your Redux store.
 - [react-router-redux](https://github.com/reactjs/react-router-redux) - Ruthlessly simple bindings to keep react-router and redux in sync.
 - [ground-control](https://github.com/raisemarketplace/ground-control) - Scalable reducer management &amp; powerful data fetching for React Router &amp; Redux.


###### Forms

 - [redux-form](https://github.com/erikras/redux-form) - A Higher Order Component using react-redux to keep form state in a Redux store.
 - [react-redux-form](https://github.com/davidkpiano/react-redux-form) - Create forms easily in React with Redux.


###### Component State

 - [redux-react-local](https://github.com/threepointone/redux-react-local) - Local component state via redux.
 - [redux-ui](https://github.com/tonyhb/redux-ui) - Easy UI state management for react redux.


# Other Integrations


###### Flux

 - [redux-actions](https://github.com/acdlite/redux-actions) - Flux Standard Action utilities for Redux.
 - [redux-promise](https://github.com/acdlite/redux-promise) - FSA-compliant promise middleware for Redux.


###### Backbone

 - [backbone-redux](https://github.com/redbooth/backbone-redux) - Easy way to keep your backbone collections and redux store in sync.


###### Falcor

 - [redux-falcor](https://github.com/ekosz/redux-falcor) - Connect your redux front-end to your falcor back-end.


###### RxJS

 - [rx-redux](https://github.com/jas-chen/rx-redux) - A reimplementation of redux using RxJS.
 - [redux-rx](https://github.com/acdlite/redux-rx) - RxJS utilities for Redux.


###### Electron

 - [redux-electron-store](https://github.com/samiskin/redux-electron-store) - A redux store enhancer that allows automatic synchronization between electron processes.


###### Deku

 - [deku-redux](https://github.com/troch/deku-redux) - Bindings for redux in deku.


# Stack Ensembles / Starter Kits / Generators / Boilerplates

 - [redux-cli](https://github.com/SpencerCDixon/redux-cli) - An opinionated CLI for building redux/react apps quicker.
 - [reactuate](https://github.com/reactuate/reactuate) - React/Redux stack (not a boilerplate kit).
 - [react-chrome-extension-boilerplate](https://github.com/jhen0409/react-chrome-extension-boilerplate) - Boilerplate for Chrome Extension React.js project.
 - [universal-redux](https://github.com/bdefore/universal-redux) - An npm package that lets you jump right into coding React and Redux with universal (isomorphic) rendering. Only manage Express setups or Webpack configurations if you want to.
 - [generator-react-aspnet-boilerplate](https://github.com/pauldotknopf/react-aspnet-boilerplate) - A starting point for building isomorphic React applications with ASP.NET Core 1, leveraging existing techniques.
 - [generator-redux](https://github.com/banderson/generator-redux) - CLI tools for Redux: next-gen functional Flux/React with devtools.
 - [generator-react-webpack-redux](https://github.com/stylesuxx/generator-react-webpack-redux) - React Webpack Generator including Redux support.
 - [socrates](https://github.com/matthewmueller/socrates) - Small (12kb), batteries-included redux stack to reduce boilerplate and promote good habits.


# Miscellaneous

 - [redux-core](https://github.com/jas-chen/redux-core) - Minimal redux.
