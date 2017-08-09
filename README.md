# CRAPSHOOT

> Create React App Plus - Super Handy, Objectively Opinionated, Tasty!

This is an opinionated approach to building a React/Redux Web Application, with an unejected instance of Create React App as its base. In addition to Redux, it comes with a bunch of goodies baked in!

## So, I can just start building like this is Create React App?

That's right! At the heart of this is an unejected Create React App instance, you can refer to the [latest Create React App readme](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md) for how to use the Create React App built in scripts.

## What's inside?

This comes with a lot of things baked in and in place already. There will eventually be a code-tour document that explains everything I've done and why, and this section will be updated as a result, but  for now... what's baked in is below

 - Redux
 - [Redux Saga](https://redux-saga.js.org/)
 - [React Router](https://reacttraining.com/react-router/)
 - [Material UI](http://www.material-ui.com/#/)
 - Two different pages
     - Routes are mounted in [`src/routes.js`](./src/routes.js)
 - A sample empty module directory to demonstrate the structure
 - A fully tested example Redux module that powers the Todo+Gifs page
     - Sagas are combined in [`src/config/sagas.js`](./src/config/sagas.js)
     - Reducers are combined in [`src/config/reducers.js`](./src/config/reducers.js)

## License

MIT