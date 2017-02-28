UI Architecture Tools and Processes
===================================

Design Process
---------------
[Google Design Sprints][gds]

[GV Design Sprints][gvds]

Material Design
---------------
[Google Design][gd]

[Material Up][matup] - daily updates of new mobile and web material designs in production.  Has a newsletter and twitter feed associated it with it.

[Material UI][reactmat] - For React

[Angular Material][angmat] - For Angular 1

[jQuery Material Design Plugins][jquerymat]


Front-End View Rendering / DOM Manipulation
-------------------------------------------

### Use ###

[React][react]

[PreactJS][preact] - Lighter weight library that uses React API.  Works well as a production build target for React--i.e., develop in React with React dev tools and then have a build task that creates a production build using Preact (it's as easy as running a different webpack loader in a prod environment)

### Know ###
[AngularJS][ang]

[jQuery][jquery]

### Explore ###
[Vue][vue]

[Angular 2][ang2]

React State Management
----------------------------------
## Use ###

[Nothing][ph] - if data flows up and down component trees without much crossing over branches horizontally much, you don't really need a special state management library.  introduce library when events on one part of the page/app start affecting distant parts of the page/app.

[Redux][redux]

  [Getting Started with Redux][reduxDev]

  [Redux DevTools][reduxDev]

## Know ##

[Flux][flux]


Misc JS Libraries
-----------------

## Know ##
[Lodash][lodash] - utility library.

## Explore ##

[Immutable JS][imjs] - immutable data structures 


[RxJs][rxjs] - reactive programming library


[Ramda][ramda] - functional programming library



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
[rxjs]: http://reactivex.io/rxjs/
[ramda]: http://ramdajs.com/
[ph]: https://github.com/petehunt/react-howto#learning-flux
[flux]: https://justgetflux.com/
[lodash]: https://lodash.com/
