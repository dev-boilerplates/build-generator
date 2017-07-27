# Development Boilerplates

**nb. add build-generator directory to your `.bin` path**to enable CLI access with this shell executable add to your dotfiles paths with `export PATH=$PATH:~/.bin/build-generator`

### Usage

    . build-generator [project-name] [boilerplate]
    
### Available stacks


*   `electron` - New Electron App wrpper **Needs `generator--electron` cloning from `vonkristoff/election`**
*	`es6` - New Basic setup using `rollup` - great for creating ES6 Classes
*   `vue` - Vue component instance boilerplate. With NPM build scripts; browserify and ES6
*	`vue-spa` Beyond the Basics boiler here, with solid setup for configuring an single-page-app for production
*   `microsite` - full static site generator with base code and build system
*	`static` - Using `Jade` as a `jekyll` alternative
*   `express` - Express app with routing infrustructure and websockets
*   `jspm` - Using JSPM package manager over Bower, and NPM scripts over Gulp. It allows one to combine any module type together, Common JS, ES6, AMD, in the same file. As well as writing ES6 using Babel.
* `wordpress` - New Wordpress Boilerplate using WP-API with Node Express as the API Router; serving static HTML with Jade for the frontend rather than PHP.
*   `exp` - the most basic HTML5 setup for fast CSS JS Experiements and prototyping. Also the default project setting, so you can leave [boilerplate] blank.
*   `requirejs` - AMD setup for JS modules, but ultimately Frameworkless.
*   `browserify` - ES6, Common JS Modules and NPM packages in the FE. Plus `Vue.js` integration.
*   `ng` - Angular boilerplate