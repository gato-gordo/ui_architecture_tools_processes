UI Architecture Tools and Processes
===================================

Design Process
---------------
[Google Design Sprints][gds]

[GV Design Sprints][gvds]

Material Design
---------------
[Google Design][gd]

[Material Up][matup] - Daily updates of new mobile and web apps that use material design principles in production.  Has a newsletter and twitter feed associated it with it.

[Material UI][reactmat] - UI kit and components for React

[Angular Material][angmat] - UI kit and components for Angular 1

[jQuery Material Design Plugins][jquerymat]


Front-End View Rendering / DOM Manipulation
-------------------------------------------

##### Use #####

[React][react]

[PreactJS][preact] - Lighter weight library that uses React API.  Works well as a production build target for React--i.e., develop in React with React dev tools and then have a build task in prod that uses Preact (it's as easy as running a different webpack loader in a prod environment)

##### Know #####
[Angular 1][ang]

[jQuery][jquery]

##### Explore #####
[Vue][vue]

[Angular 2][ang2]

React State Management
----------------------------------
##### Use #####

[Nothing][ph] - If data and app state flows up and down component trees without crossing over tree branches "horizontally" much, then you don't really need a special state management library.  Introduce a library when events in one part of the page/app start affecting distant parts of the page/app.

[Redux][redux]

  * [Getting Started with Redux][reduxDev]

  * [Redux DevTools][reduxDev]

##### Know #####

[Flux][flux]

Misc JS Libraries
-----------------

##### Know #####
[Lodash][lodash] - utility library

##### Explore #####

[Immutable JS][imjs] - immutable data structures 

[RxJs][rxjs] - reactive programming library

[Ramda][ramda] - functional programming library

Unit Testing
-----------------
##### Use #####
[Mocha][mocha] - test framework for Node.js and browser code

[Chai][chai] - BDD /TDD style assertion library used with Mocha

[Sinon][sinon] - test mocks, stubs, spies used with Mocha

[Jest][jest] - React component tester.  Shallow renders the component in isolation and allows you to test the render against
an earlier canonical snapshot that was taken.  Good for UI regression testing.

[Supertest][supertest] - server-side api testing

End-to-End Testing
------------------
##### Use #####
[Webdriver.io][wdio] - Selenium headless browser and web automation for Node

Module Bundling and Build Tools
-------------------------------
##### Use #####
[Webpack][wp] 

[npm scripts][npms]

##### Know #####
[Grunt][grunt]

[Gulp][gulp]

CSS Pre-processors
-----------------
##### Use #####

[Sass][sass]

Ajax
--------------
##### Use #####
[Fetch API][fetch] - promise-based native web api for http requests.  [Polyfill][fetchPoly] until it has universal browser support.

##### Explore #####
[Axios][axios]

Server  API
-----------
##### Use #####
[Restify][restify]

##### Know #####
[Express][express]

##### Explore #####
[Hapi][hapi]

[Koa][koa]

Node
----
##### Use #####
[6.x][node6]

##### Explore #####
[7.x][node7]


[gvds]: https://www.youtube.com/watch?v=7zOBMxRYJ7I&list=PLNKW8GAxivxcwqF2OU7UvjkT_lPMqz_C8
[gds]: https://www.youtube.com/playlist?list=PLoSlBC4J_CK9tcVl_ZnVDHi7Xm0QTCNB4
[gd]: https://design.google.com/resources/
[matup]: https://material.uplabs.com/
[react]: https://facebook.github.io/react/
[preact]: https://preactjs.com/
[ang]: https://angularjs.org/
[ang2]: https://angular.io/
[vue]: https://vuejs.org/
[sin]: http://sinonjs.org/
[reactmat]: http://www.material-ui.com/#/
[angmat]: https://material.angularjs.org/latest/
[redux]: http://redux.js.org/
[reduxDev]: https://github.com/gaearon/redux-devtools
[jquery]: https://jquery.com/
[jquerymat]:  http://www.jqueryscript.net/tags.php?/Material%20Design/
[imjs]: https://facebook.github.io/immutable-js/
[wdio]: http://webdriver.io/
[rxjs]: http://reactivex.io/rxjs/
[ramda]: http://ramdajs.com/
[ph]: https://github.com/petehunt/react-howto#learning-flux
[flux]: https://justgetflux.com/
[lodash]: https://lodash.com/
[supertest]: https://github.com/visionmedia/supertest
[mocha]: https://mochajs.org/
[chai]: http://chaijs.com/
[sinon]: http://sinonjs.org/
[jest]: https://facebook.github.io/jest/
[sass]: http://sass-lang.com/
[express]: http://expressjs.com/
[fetch]: https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API
[fetchPoly]:  https://github.com/github/fetch
[axios]: https://github.com/mzabriskie/axios
[koa]: http://koajs.com/
[hapi]: https://hapijs.com/
[restify]: http://mcavage.me/node-restify/
[wp]: https://webpack.github.io/
[node6]: https://nodejs.org/en/blog/release/v6.0.0/
[node7]: https://nodejs.org/en/blog/release/v7.0.0/
[gulp]: http://gulpjs.com/
[grunt]: https://gruntjs.com/
[npms]: https://docs.npmjs.com/misc/scripts
