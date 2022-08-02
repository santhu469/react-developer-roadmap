# React Developer Roadmap

> Roadmap to becoming a React developer:

## Disclaimer
> The purpose of this roadmap is to give you an idea about the landscape. The road map will guide you if you are confused about what to learn next, rather than encouraging you to pick what is hip and trendy. You should grow some understanding of why one tool would be better suited for some cases than the other and remember hip and trendy does not always mean best suited for the job

<!-- ## Roadmap -->

<!-- ![Roadmap](./roadmap.png) -->

## Resources

1. Basics
    1. HTML
        * Learn the basics of all HTML Tags and Behaviour (nav, header, footer, headers, paragraph, form, inputs, select, radio, checkbox, sections, blocked, non-blocked, buttons, strong, blod)
        * Make a few pages as an exercise
    2. CSS
        * Learn the basics of CSS
        * Style pages from previous step
        * Build a page with grid and flexbox
    3. Code editors
        * VS Code
        * Sublime Text
        * Atom, etc.
    4. JS Basics
        * Get familiar with the syntax
        * Data Types
        * Variables and Scope
        * Operators
        * Objects and Arrays
        * Functions
        * Callbacks, promises, async await
        * Conditions and Loops
        * Learn basic operations on DOM
        * Learn mechanisms typical for JS (Hoisting, Event Bubbling, Prototyping, event looping)
        * Make some AJAX (XHR) calls
        * Learn new features (ECMA Script 6+)
        * Additionally, get familiar with the jQuery library
    - Keep in mind every time
        * code intendation and beautify (setup in your code editor)
        * [javascript.info](https://javascript.info/)
        * [javascript](developer.mozilla)
        * [w3shools](https://www.w3schools.com/js/default.asp)
    - es6
        * [babeljs](https://babeljs.io/docs/en/learn) Learn ES2015
        * [ECMAScript 6](https://github.com/lukehoban/es6features)
2. General Development Skills
    1. Learn about version controll systems
    2. Learn GIT, create a tasks repositories on GitHub, share your code with other people, SSH key adding for authentication
    3. Learn all git commands and usages
    4. Know HTTP(S) protocol, request methods (GET, POST, PUT, PATCH, DELETE, OPTIONS) formally called REST API calls
    <!-- 5. Don't be afraid of using Google, [Power Searching with Google](http://www.powersearchingwithgoogle.com/) -->
    5. Get familiar with terminal, configure your shell (bash, zsh, fish) depends on the OS your are using
    6. Read a few books about algorithms and data structures
    7. Read a few books about design patterns
    8. Javascript design patterns
3. Learn React on [official website](https://reactjs.org/tutorial/tutorial.html)
4. Get familiar with tools that you will be using
    1. Package Managers
        * [npm](https://www.npmjs.com/)
        * [yarn](https://yarnpkg.com/lang/en/)
        * difference between [npm] and [yarn]
        * [pnpm](https://pnpm.js.org/)
        - recommended ([npm] [yarn])
    2. Task Runners
        * [npm scripts](https://docs.npmjs.com/misc/scripts)
        * [gulp](https://gulpjs.com/)
        * [Webpack](https://webpack.js.org/)
        * [Rollup](https://rollupjs.org/guide/en)
        * [Parcel](https://parceljs.org/)
        - mostly used webpack
5. Styling
    1. CSS Preprocessor
        * [Sass/CSS](https://sass-lang.com/)
        * [PostCSS](https://postcss.org/)
        * [Less](http://lesscss.org/)
        * [Stylus](http://stylus-lang.com/)
        - know how to convert SASS and SCSS into CSS
    2. CSS Frameworks
        * [Bootstrap](https://getbootstrap.com/)
        * [Materialize](https://materializecss.com/), [Material UI](https://material-ui.com/), [Ant Design](https://ant.design) [Material Design Lite](https://getmdl.io/)
        * [Bulma](https://bulma.io/)
        * [Semantic UI](https://semantic-ui.com/)
    3. CSS Architecture
        * [BEM](http://getbem.com/)
        * [CSS Modules](https://github.com/css-modules/css-modules)
        * [Atomic](https://acss.io/)
        * [OOCSS](https://github.com/stubbornella/oocss/wiki)
        * [SMACSS](https://smacss.com/)
        * [SUITCSS](https://suitcss.github.io/)
    4. CSS in JS
        * [Styled Components](https://www.styled-components.com/)
        * [Radium](https://formidable.com/open-source/radium/)
        * [Emotion](https://emotion.sh/)
        * [JSS](http://cssinjs.org/)
        * [Aphrodite](https://github.com/Khan/aphrodite)
6. State Management
    1. [Component State](https://reactjs.org/docs/faq-state.html)/[Context API](https://reactjs.org/docs/context.html)
    2. [Redux](https://redux.js.org/)
        - First Know about Flux patterns for state management
        1. Async actions (Side Effects)
            * [Redux Thunk](https://github.com/reduxjs/redux-thunk)
            * [Redux Better Promise](https://github.com/Lukasz-pluszczewski/redux-better-promise)
            * [Redux Saga](https://redux-saga.js.org/)
            * [Redux Observable](https://redux-observable.js.org)
        2. Helpers
            * [Rematch](https://rematch.gitbooks.io/rematch/)
            * [Reselect](https://github.com/reduxjs/reselect)
        3. Data persistence
            * [Redux Persist](https://github.com/rt2zz/redux-persist)
            * [Redux Phoenix](https://github.com/adam-golab/redux-phoenix)
        4. [Redux Form](https://redux-form.com)
    3. [MobX](https://mobx.js.org/)
7. Type Checkers
    * [PropTypes](https://reactjs.org/docs/typechecking-with-proptypes.html)
    * [TypeScript](https://www.typescriptlang.org/)
    * [Flow](https://flow.org/en/)
8. Form Helpers
    * [Redux Form](https://redux-form.com)
    * [Formik](https://github.com/jaredpalmer/formik)
    * [Formsy](https://github.com/formsy/formsy-react)
    * [Final Form](https://github.com/final-form/final-form)
    - recommended [Formik](https://github.com/jaredpalmer/formik)
9. Routing
    * [React-Router](https://reacttraining.com/react-router/)
    * [Router5](https://router5.js.org/)
    * [Redux-First Router](https://github.com/faceyspacey/redux-first-router)
    * [Reach Router](https://reach.tech/router/)
    - recommended and most using[React-Router](https://reacttraining.com/react-router/)
10. API Clients
    1. REST
        * [axios](https://github.com/axios/axios)
        * [SuperAgent](https://visionmedia.github.io/superagent/)
        * [Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
        - recommended and most using [axios](https://github.com/axios/axios)
    2. API Developing and Testing Tools
        * [Postman](https://www.postman.com/)
        * [Swager](https://www.postman.com/)
    2. GraphQL
        * [Apollo](https://www.apollographql.com/docs/react/)
        * [Relay](https://facebook.github.io/relay/)
        * [urql](https://github.com/FormidableLabs/urql)
11. Utility Libraries
    * [Lodash](https://lodash.com/)
    * [Moment](https://momentjs.com/)
    * [classnames](https://github.com/JedWatson/classnames)
    * [Numeral](http://numeraljs.com/)
    * [RxJS](http://reactivex.io/)
    * [ImmutableJS](https://facebook.github.io/immutable-js/)
    * [Ramda](https://ramdajs.com/)
12. Testing
    1. Unit Testing
        * [Jest](https://facebook.github.io/jest/)
        * [Enzyme](http://airbnb.io/enzyme/)
        * [Sinon](http://sinonjs.org/)
        * [Mocha](https://mochajs.org/)
        * [Chai](http://www.chaijs.com/)
        * [AVA](https://github.com/avajs/ava)
        * [Tape](https://github.com/substack/tape)
        - recommended [Jest](https://facebook.github.io/jest/)
    2. End to End Testing
        * [Selenium](https://www.seleniumhq.org/), [Webdriver](http://webdriver.io/)
        * [Cypress](https://cypress.io/)
        * [Puppeteer](https://pptr.dev/)
        * [Cucumber.js](https://github.com/cucumber/cucumber-js)
        * [Nightwatch.js](http://nightwatchjs.org/)
        - for testing purpose (good to know)
    3. Integration Testing
        * [Karma](https://karma-runner.github.io/)
13. Internationalization
    * [React Intl](https://github.com/yahoo/react-intl)
    * [React i18next](https://react.i18next.com/)
14. Server Side Rendering
    * [Next.js](https://nextjs.org/)
    * [After.js](https://github.com/jaredpalmer/after.js)
    * [Rogue](https://github.com/alidcastano/rogue.js)
    - recommended [Next.js](https://nextjs.org/)
    - create one sample project with [Next.js](https://nextjs.org/) 
15. Static Site Generator
    * [Gatsby](https://www.gatsbyjs.org/)
<!-- 16. Backend Framework Integration
    * [React on Rails](https://shakacode.gitbooks.io/react-on-rails/content/) -->
16. Deployment
    * AWS basics - cloud (good to know)
    * Free web hosting (heroku, netlify, github)
17. Mobile (good to know)
    * [React Native](https://facebook.github.io/react-native/)
    * [Cordova](https://cordova.apache.org/)/[Phonegap](https://phonegap.com/)
    * [Ionic] (https://ionic.io/framework)
    - recommended [React Native](https://facebook.github.io/react-native/)
18. Desktop (good to know)
    * [Proton Native](https://proton-native.js.org/)
    * [Electron](https://electronjs.org/)
    * [React Native Windows](https://github.com/Microsoft/react-native-windows)
    - recommended [Electron](https://electronjs.org/)
<!-- 19. Virtual Reality
    * [React 360](https://facebook.github.io/react-360/) -->
19. Alternative for reactjs
    - good to know about ohter js frameworks 
    * [Angular](https://angular.io/start)
    * [Vuejs](https://vuejs.org/)

20. Tasks
    * Accordion ex: [sample](https://react-projects-4-accordion.netlify.app/) 
    - using functinal and class components
    * [Color generator](https://react-projects-9-color-generator.netlify.app/)
    - using react hooks
    * Create menu for restraunt ex: [sample](https://react-projects-5-menu.netlify.app/): take sample json data, create search, add menu item in the modal, update the menu item, side menu, navbar footer, pagination on page scroll(like instagram, linkedin etc.)
    - React, react router, hooks, material ui (without form helper)

<!-- ## Wrap Up

If you think the roadmap can be improved, please do open a PR with any updates and submit any issues. Also, I will continue to improve this, so you might want to star this repository to revisit. -->

<!-- ## Contribution

The roadmap is built using [Draw.io](https://www.draw.io/). Project file can be found at `/src` directory. To modify it, open draw.io, click **Open Existing Diagram** and choose `xml` file with project. It will open the roadmap for you. Update it, upload and update the images in readme and create a PR (export as png).

- Open a pull request with improvements
- Discuss ideas in issues
- Spread the word -->

<!-- ## License

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/) -->
