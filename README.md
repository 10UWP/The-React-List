
# :space_invader: The-React-List

When you are stuck using Javascript, React can help with it's component architecture or maybe you will use it becuase it has become a tidal wave... :o: Rant :o: Over 90% of Desktop PC's run Windows and the number of React tools that are not tested on Windows boggles the rational human mind. Even Facebook, has had a long standing issue with both Flow and Nuclide that has only recently as of Sept 2016 are becoming workable.

# Key Items

[create-react-app](https://github.com/facebookincubator/create-react-app) Facebook's official starting point

[Nuclide](https://github.com/facebook/nuclide)  [Nuclide.io](https://nuclide.io/) An open IDE for web and native mobile development, built on top of Atom http://nuclide.io 
- See next section for details on Nuclide.

[WatchMan](https://facebook.github.io/watchman/) Watchman exists to watch files and record when they change. It can also trigger actions (such as rebuilding assets) when matching files change. [GitHub](https://github.com/facebook/watchman) - [Install](https://facebook.github.io/watchman/docs/install.html) - [Windows Issues](https://github.com/facebook/watchman/issues/19) Watchman provides both a real-time file change subscription mechanism (echoing what the native OS facilities provide, but in a cross-platform way) and functionality to query the view of the filesystem without talking to the filesystem. The latter part of this may sound strange, but when you are dealing with a very large directory tree, the act of looking at a "cold" portion of it can block for a non-trivial amount of time. Whether watchman is necessary depends on your needs.

[React Developer Tools](https://github.com/facebook/react-devtools) An [extension](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi) that allows inspection of React component hierarchy in [Chrome Developer Tools](https://github.com/facebook/react-devtools/tree/master/shells). And [Firefox too](https://addons.mozilla.org/en-US/firefox/addon/react-devtools/) and [Electron](https://github.com/facebook/react-devtools/tree/master/shells)

[DevTools for Redux](https://github.com/gaearon/redux-devtools  DevTools for Redux with hot reloading, action replay, and customizable UI 
http://youtube.com/watch?v=xsSnOQynTHs

[Install MongoDB on Windows](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/) Required by some React applications.


[The Current Node.js](https://nodejs.org/en/download/current/) Select 64 bit such as [Node.js 7.1.0 64 bit for example](https://nodejs.org/dist/v7.1.0/win-x64/node.exe)

# Nuclide

[Nuclide](https://github.com/facebook/nuclide)  [Nuclide.io](https://nuclide.io/) An open IDE for web and native mobile development, built on top of Atom http://nuclide.io

:o: Mostly, Facebook stuff works well on Windows with odd areas of incompetence such as Nuclide which has been on a long and tortured journey to be "mostly working" - https://github.com/facebook/nuclide/issues/321

- [full documentation for Nuclide](http://nuclide.io/docs)
-  [Client Installation](http://nuclide.io/docs/editor/setup/#windows)
-  [Server Installation](http://nuclide.io/docs/editor/setup/#installing-nuclide-server)
- [Getting Started Feature Walkthroughh](http://nuclide.io/docs/quick-start/getting-started/)

By default, Nuclide does not install all of the recommended Atom packages that enhance the Nuclide experience.
Recommended packages include:

-    tool-bar to enable the Nuclide toolbar.
-    sort-lines to enable sorting lines of text.
-    language-ocaml to enable OCaml language syntax highlighting.
-    language-babel to enable language grammar for JS, Flow and React JS, etc.
-    …and others under package-deps.


In order to install all of the recommended packages:

 -   Go to Packages | Settings View | Manage Packages.
 -   Search for the nuclide package, and click on the package’s Settings button.
 -   Select the Install Recommended Packages on Startup checkbox.
    
Installing Nuclide Server


If you want to use Nuclide for remote development, you’ll also need to set up the npm nuclide package. Instructions can be found in the Remote Development docs.


Other Installations

To benefit from all of Nuclide’s features, we recommend you also install the following:

-    Watchman - version 3.2 or above. It must be in /usr/local/bin/ or in your $PATH environment variable.   Without Watchman, Nuclide will lose some functionality of its Mercurial, Remote Development, and Quick Open features.
-    [Flow](https://nuclide.io/docs/languages/flow/) Nuclide has deep, built-in support for [Flow-enabled JavaScript](http://flowtype.org/).   [Flow recently became supported on Windows](https://flowtype.org/blog/2016/08/01/Windows-Support.html)
-    [Hack](https://nuclide.io/docs/languages/hack/) Nuclide has been built from the start to provide a great IDE experience for Hack development. Hack is a programming language for [HHVM](http://hhvm.com/) and HVVM is a performance enhanced PHP with Hack glued on top.  Currently, HHVM is not supported on Windows, so this integration has limited viability on that platform. However, [work is being done to port HHVM to Windows](https://github.com/facebook/hhvm/issues/5460).
-    [Mercurial](https://nuclide.io/docs/features/hg/) - Atom provides [Git support in its core packages](https://atom.io/docs/v1.5.3/using-atom-version-control-in-atom). Given Facebook’s heavy use of Mercurial, Nuclide extends Atom’s source control integration with support for Mercurial.   Nuclide’s support for Mercurial is much more full-featured that its support for Git. Nuclide has not yet tried to extend the default support for Git provided by Atom.

 

## If Victorian Engineers had Invented React Instead of Facebook

Whispers of Brass and Steam Engines...

[Chugga chugga Choo Choo](http://react-cosmos.github.io/react-cosmos/?component=FlatrisGame&fixture=new-game-running)

![](https://avatars0.githubusercontent.com/u/23018767?v=3&s=200)

[React Cosmos](https://github.com/react-cosmos/react-cosmos) and   [React Cosmos Atom](https://github.com/react-cosmos/react-cosmos-atom)

[Component Playground](https://github.com/FormidableLabs/component-playground) A component for rendering React components with editable source and live preview https://formidable.com/open-source/component-playground/

[react pixi](https://github.com/Izzimach/react-pixi)  Create/control a [Pixi.js](https://github.com/pixijs/pixi.js) canvas using React

[react three renderer](https://github.com/toxicFork/react-three-renderer)  Render into a three.js canvas using React. https://toxicfork.github.com/react-three-renderer-example/
[draft-js](https://github.com/facebook/draft-js) A React framework for building text editors. https://facebook.github.io/draft-js/

[React Server](https://react-server.io/) the ideas behind [Facebook's Big Pipe](https://www.facebook.com/notes/facebook-engineering/bigpipe-pipelining-web-pages-for-high-performance/389414033919/), to make sure that your site shows up as quickly as humanly possible for your users. Once you're hungry for more, dig into the [docs](https://react-server.io/docs) and [react-server](https://github.com/redfin/react-server) itself. If you find performance annoying, you need to get [Slo, Bro](https://github.com/tfe/slowbro).

# CMS

### Keystone

[Keystone](http://keystonejs.com/) The Version 4 release of the Keystone Node.js based CMS will be based on React. 
- See the Master branch at https://github.com/keystonejs/keystone


:o: Instaltion fails on Windows due to somme dippy dep - http://keystonejs.com/getting-started/

### Gatsby

[Gatsby](https://github.com/gatsbyjs/gatsby) Transform plain text into dynamic blogs and websites using React.js

-  No-refresh page transitions
-    The awesome React.js component model
-    Live editing on every part of your site. Dramatically speed development.
- Transform plain text into dynamic blogs and websites using the latest web technologies. A React.js static site generator.
- Supports Markdown, HTML, and React.js pages out of the box. Easy to add support for additional files types.
- Leverages React's component model and React Router's "nested component hierarchy" to make templating incredibly powerful and intuitive.
- All templates, css, and content are hot reloadable — powered by Webpack.
- Build sites like it's 1995. Files are translated into HTML pages at the same position within the file system. Add a markdown file at /docs/index.md and it'll be converted to /docs/index.html.
- No-reload page transitions
-    Hot reload editing. Tweak your pages, templates, and styles and see changes in real time.
-    Make React.js component model and ecosystem available for building static sites
-    Intuitive directory-based URLs. The URL of a page is derived from its spot on the file system.
-    Support "Starters" — install starter sites directly from Github. Use open sourced starters or build your own.

### Gatsby Tools:
[Import your old & busted site or blog for use with Jekyll](http://import.jekyllrb.com/) Wide Range of Available Importers - Converts Wordpress etc to Markdown files suitable for Gatsby

[gatsby-starter-default](https://github.com/gatsbyjs/gatsby-starter-default) The default Gatsby starter http://gatsbyjs.github.io/gatsby-starter-default/

[Lumen](https://github.com/wpioneer/gatsby-starter-lumen) Simple starter for Gatsby http://wpioneer.github.io/gatsby-starter-lumen/

[gatsby-starter-drunkenblog](https://github.com/konsumer/gatsby-starter-drunkenblog) A gatsby starter blog with a few more frills.

[gatsby-starter-documentation](https://github.com/gatsbyjs/gatsby-starter-documentation)

[gatsby-starter-blog](https://github.com/gatsbyjs/gatsby-starter-blog) Gatsby starter for creating a blog http://gatsbyjs.github.io/gatsby-starter-blog/ Install this starter (assuming Gatsby is installed) by running from your CLI: gatsby new gatsby-blog https://github.com/gatsbyjs/gatsby-starter-blog

[gh-pages](https://www.npmjs.com/package/gh-pages) Publish to a gh-pages branch on GitHub (or any other branch on any other remote)

[markdown-it](https://github.com/markdown-it/markdown-it) Markdown parser, done right. 100% CommonMark support, extensions, syntax plugins & high speed https://markdown-it.github.io  [Markdown-it Plugins](https://www.npmjs.com/browse/keyword/markdown-it-plugin)

[Webpack Plugins](https://webpack.github.io/docs/list-of-plugins.html)

[Webpack Configurator](https://github.com/lewie9021/webpack-configurator) Utility library for creating and extending Webpack configuration structures.

[Webpack List of Loaders](https://webpack.github.io/docs/list-of-loaders.html)
- [SVG to React Loader](https://github.com/jhamlet/svg-react-loader)
- [svg-as-symbol-loader](https://github.com/bhovhannes/svg-as-symbol-loader)
- [Icons loader (generate iconfonts for webpack)](https://www.npmjs.com/package/icons-loader)
- [inline markups to HTML: SVG, MathML, etc](https://www.npmjs.com/package/markup-inline-loader)
- [React Hot Loader](https://github.com/gaearon/react-hot-loader) Tweak React components in real time. http://gaearon.github.io/react-hot-loader/
- [line-art-loader](https://github.com/tptee/line-art-loader) A Webpack loader that inlines SVG files, converting all of its nodes to paths. Useful for line art animations.
- [react-templates loader for webpack](https://github.com/AlexanderPavlenko/react-templates-loader)
- [React Markdown](https://github.com/javiercf/react-markdown-loader) This loader parses markdown files and converts them to a React Stateless Component. It will also parse FrontMatter to import dependencies and render components along with it’s source code. We developed this loader in order to make the process of creating styleguides for React components easier

[A Step-by-Step Guide: Gatsby on Netlify](https://www.netlify.com/blog/2016/02/24/a-step-by-step-guide-gatsby-on-netlify/)  Today, we’re going to look at how to host a website built with Gatsby on Netlify, including setting up continuous deployment. Gatsby is a new static site generator, but it’s gaining traction fast! It’s made in what’s probably the only thing as hot as Google’s ‘go’ right now, React.js. React is a hugely popular javascript framework out of Facebook.

[Hosting GatsbyJS - A React Static Site Generator](https://www.aerobatic.com/blog/gatsbyjs) Gatsby transforms plain text into dynamic blogs and websites using the latest web technologies. It’s easy to get started with — and host on Aerobatic. I’ll go over why you should consider it, and how to get it up and running quickly with Aerobatic.

[blog.scottnonnenberg.com](https://github.com/scottnonnenberg/blog) 
- More on how to use this project: https://blog.scottnonnenberg.com/this-blog-is-now-open-source/ 
- [Static site generation with Gatsby.js](https://blog.scottnonnenberg.com/static-site-generation-with-gatsby-js/)
- [Practical Gatsby.js](https://blog.scottnonnenberg.com/practical-gatsby-js/)


### Relax

[Relax](https://github.com/relax/relax) New generation CMS on top of React, Redux and GraphQL http://demo.getrelax.io/admin

- Relax is a powerful new generation CMS on top of React and Node.js which aims for a better way of building websites.
- It features a live page builder based on components and a smart and easy way of binding dynamic data to them.


:o: Installation fails on Windows (and probably everywhere) if you have Python 3.5 installed instead of some old retro Python 2 hardcoded dep.

### Phenomic

[Phenomic](https://github.com/MoOx/phenomic)  😱 Modern static* website generator based on the React and Webpack ecosystem ✨ https://phenomic.io/ 

- [How to setup Phenomic](https://phenomic.io/docs/setup/)
- [Getting started with Phenomic](https://phenomic.io/docs/getting-started/)
- [See who's using Phenomic](https://phenomic.io/showcase/)

[What are the differences with Gatsby?](https://phenomic.io/docs/faq/gatsby/)
- Phenomic will load pages data on demand only so it can be used for website/app with a lot of pages/screen.
- Phenomic offers offline browsing via Service Worker.
- Phenomic uses peer dependencies so you have total control over the dependencies. You will never have to wait to use latest React version if it's compatible with your code and Phenomic requirements (eg: React 0.14 or 15.0, you decide).
- Phenomic does not have any "optional" dependencies as a real dependency. For example, Gatsby has in it's dependencies LESS, Sass and PostCSS (yeah maybe that's too much). By default, Phenomic will just install PostCSS (since it's required in the phenomic-theme-base), but you can remove it (since it will be added in your package.json) and replace with any dependency you want (or none).
- Phenomic is covered by a lot of automated unit, integration and functional tests to avoid bugs and regressions.


:o: Installation fails on Windows due to some dippy dep. https://phenomic.io/docs/setup/


### Boldr

[Boldr](https://github.com/boldr/boldr) Universal React CMS. Built for the modern developer. React, Postgres, Express, Webpack 2 and Docker. https://staging.boldr.io

### Antwar

[Antwar](https://github.com/antwarjs/antwar) A static site generator built with React and Webpack. http://antwarjs.github.io/ - [Getting Started](http://antwarjs.github.io/docs/getting-started/)

### react2html

[react2html](https://github.com/modesty/react2html) A component based web site starter kit and build tool, built with ReactJS, SASS, Babel, WebPack and Node.js.
- React2Html is a component based web site starter kit and build tool. It enables build-time data-driven reusable components for building multi-page website with compsability and efficiency, powered by ReactJS, SASS, Babel, WebPack and Node.js.
- Component Based Web Application prompts data-driven reusable components for developing web applications. React2Html is a starter kit and build tool to enable component based development for web sites: static web site or service oriented HTML application can utilize the same data driven reusable component model to improve the effectiveness of site development and updates. 
- With React2Html, a multi-page static site can be built by composing reusable functional stateless components, then generates HTML with data models through build process. Runtime model update (user interactions or Ajax) and rendering through Virtual DOM has been covered very well in React.js, it's optional with React2HTML: in addition to 'react to changes' at run time, React2Html focus on build-time component re-usability. 



### Sitegen

[Sitegen](https://github.com/andreypopp/sitegen) Generate websites by composing React components http://andreypopp.github.io/sitegen/ - Sitegen is a static site generator based on Webpack and React. Sitegen's motivation is to provide a framework for content based sites with simple API to take the advantage of React component model and rich Webpack ecosystem.


# Converters

[Import your old & busted site or blog for use with Jekyll](http://import.jekyllrb.com/) Wide Range of Available Importers - Converts Wordpress etc to Markdown files

[React-Magic and HTMLtoJSX](https://github.com/reactjs/react-magic) Automatically AJAXify plain HTML with the power of React. It's magic!
- React-Magic is an experimental library that uses the power of Facebook's React library to inject AJAX-loading goodness into plain old HTML webpages, without having to write any custom JavaScript. You can even use CSS transitions between the pages. Simply add a single script tag (or click a bookmarklet) and "it just works".
- [HTMLtoJSX](http://magic.reactjs.net/htmltojsx.htm) is a component of React-Magic that converts HTML to JSX. It can be used standalone, either on the web or via Node.js.

[html-to-react](https://github.com/aknuds1/html-to-react) A lightweight library that converts raw HTML to a React DOM structure.

[html to React Components](https://github.com/roman01la/html-to-react-components) Extract annotated portions of HTML into React components as separate modules. http://roman01la.github.io/html-to-react-components/ This utility was designed to free React developers from a boring work of translating HTML into components.  Imagine you just got a pile of HTML from your designers. The first thing you will do is break HTML into React components. This is boring and we can automate this.

[grunt-html2jsx](https://github.com/hemanth/grunt-html2jsx) Converts HTML to JSX for use with React.

[Extract to React Chrome DevTools Plugin](https://github.com/jesstelford/extract-to-react) Chrome/Chromium extension for easy HTML to React conversion. Extract all the HTML & CSS of any portion of any website directly into a ready-to-go React Component! It is possible to split a monolithic component up into multiple nested components.

[gulp-jsxify](https://github.com/parroit/gulp-jsxify) gulp plugin to convert html files to react jsx

[HTML2React](https://github.com/Deschtex/html2react) A utility for turning raw HTML into React elements. If you want to take raw HTML, SVG or any arbitrary XML and turn it into something that you can use in a React application, without using dangerouslySetInnerHTML, then you can simply pass it to html2react: A powerful feature of html2react is the ability to target elements in the provided HTML and override them with React components, using nothing but CSS selectors for the mapping. Super simple! The following example maps any <a> tag in the HTML to the local Link component:

[React HTML Parser](https://github.com/wrakky/react-html-parser) Converts HTML string directly into React components avoiding the need to use dangerouslySetInnerHTML]()

[reacterminator](https://github.com/poetic/reacterminator) Reacterminator converts html into es6 react components. To get started, annotate your html tags with several simple data attributes that reacterminator recognizes. For example, you can add a data-component-name attribute to your html to let reacterminator know that it is a react component:




# Starter Kits and Boilerplates

[ASP.NET Starter Kit](https://github.com/kriasoft/aspnet-starter-kit) Cross-platform web development with Visual Studio Code, C#, F#, JavaScript, ASP.NET Core, EF Core, React (ReactJS), Redux, Babel. Single-page application boilerplate. https://twitter.com/dotnetreact

ASP.NET Core Starter Kit is a real-world boilerplate and tooling for creating single-page web applications (SPA) oriented towards progressive enhancement design, cross-platform compatability and component-based UI architecture. It is built upon best of breed technologies including .NET Core, Kestrel, EF Core, Babel, Webpack, React, Redux, CSS Modules, React Hot Loader and more. This boilerplate comes in both C# and F# flavors.
- Component-based front-end development via Webpack, CSS Modules and React (see webpack.config.js)
- Modern JavaScript syntax (ES2015+) via Babel; modern CSS syntax (CSS3+) via PostCSS
- Application state management via Redux (see client/store.js)
- Universal cross-stack routing and navigation via path-to-regexp and history (see client/routes.json)
- Code-splitting and async chunk loading with Webpack and ES6 System.import()
- Hot Module Replacement (HMR) /w React Hot Loader
- Lightweight build automation with plain JavaScript (see run.js)
- Cross-device testing with Browsersync
- Git-based deployment to Azure App Service (see run.js/publish)
    
[React Starter Kit](https://github.com/kriasoft/react-starter-kit) React Starter Kit — isomorphic web app boilerplate (Node.js, Express, GraphQL, React.js, Babel 6, PostCSS, Webpack, Browsersync) https://www.reactstarterkit.com

React Starter Kit is an opinionated boilerplate for web development built on top of Node.js, Express, GraphQL and React, containing modern web development tools such as Webpack, Babel and Browsersync. Helping you to stay productive following the best practices. A solid starting point for both professionals and newcomers to the industry.

[Este](https://github.com/este/este) Starter kit for full–fledged React apps. One stack for browser, mobile, server. https://este.firebaseapp.com/
-    react and react native
-    redux
-    babeljs
-    immutablejs
-    react-router
-    react-router-redux
-    react-intl
-    redux-storage
-    webpack
-    expressjs
-    eslint
-    formatjs Universal internationalization.
-    react-helmet A document head manager for React.
-    webpack-isomorphic-tools
-    chriso/validator.js For simple yet powerfull Este sync/async validation.
-    bluebird Because it's better than native implementation.
-    AVA Futuristic JavaScript test runner.
-    SASS or plain CSS with autoprefixer
-    uuid Generate RFC-compliant UUIDs in JavaScript.
-    react-native-uuid node-uuid for react-native.
-    gulp Aren't NPM scripts better? No.
-    raven-js Crash reporting client for Sentry.
-    gulp-real-favicon Generate a multiplatform favicon with RealFaviconGenerator
-    react-native-fbsdk For Facebook Login in React Native. Follow the readme install notes.
-    And much more. Explore the repository.

[react boilerplate](https://github.com/mxstbr/react-boilerplate)  🔥 A highly scalable, offline-first foundation with the best developer experience and a focus on performance and best practices. http://reactboilerplate.com Start your next react project in seconds A highly scalable, offline-first foundation with the best DX and a focus on performance and best practices
- Quick scaffolding - Create components, containers, routes, selectors and sagas - and their tests - right from the CLI!
- Instant feedback -    Enjoy the best DX (Developer eXperience) and code your app at the speed of thought! Your saved changes to the CSS and JS are reflected instantaneously without refreshing the page. Preserve application state even when you update something in the underlying code!
- Predictable state management - Unidirectional data flow allows for change logging and time travel debugging.
- Next generation JavaScript - Use template strings, object destructuring, arrow functions, JSX syntax and more, today.
- Next generation CSS - Write composable CSS that's co-located with your components for complete modularity. Unique generated class names keep the specificity low while eliminating style clashes. Ship only the styles that are on the page for the best performance.
- Industry-standard routing -  It's natural to want to add pages (e.g. `/about`) to your application, and routing makes this possible.
- Industry-standard i18n internationalization support -   Scalable apps need to support multiple languages, easily add and support multiple languages with `react-intl`.
- Offline-first - The next frontier in performant web apps: availability without a network connection from the instant your users load the app.
- SEO - We support SEO (document head tags management) for search engines that support indexing of JavaScript content. (eg. Google)
-    The best test setup: Automatically guarantee code quality and non-breaking changes. (Seen a react app with 99% test coverage before?)
-    Native web app: Your app's new home? The home screen of your users' phones.
-    The fastest fonts: Say goodbye to vacant text.
-    Stay fast: Profile your app's performance from the comfort of your command line!
-    Catch problems: AppVeyor and TravisCI setups included by default, so your tests get run automatically on Windows and Unix.
- There’s also a fantastic [video](https://vimeo.com/168648012) on how to structure your React.js apps with scalability in mind. It provides rationale for the majority of boilerplate's design decisions.



[typescript-react-redux-starter](https://github.com/rangle/typescript-react-redux-starter) Typescript, React, Redux, Webpack starter kit

[react-redux-starter-kit](https://github.com/davezuko/react-redux-starter-kit) This starter kit is designed to get you up and running with a bunch of awesome new front-end technologies, all on top of a configurable, feature-rich webpack build system that's already setup to provide hot reloading, CSS modules with Sass support, unit testing, code coverage reports, bundle splitting, and a whole lot more.
-    react
-    redux
-    react-router
-    react-router-redux
-    webpack
-    babel
-    koa
-    karma
-    eslint

[React Slingshot](https://github.com/coryhouse/react-slingshot) React + Redux starter kit / boilerplate with Babel, hot reloading, testing, linting and a working example app, all built in

[react-flux-starter-kit](https://github.com/coryhouse/react-flux-starter-kit) A quick way to get rolling with React and Flux using Browserify and Gulp

- React, React Router, and Flux for ultra-responsive UI development
- Browserify bundling
- jQuery with Bootstrap for styling
- Gulp build that:
-- compiles JSX
-- lints JSX and JS via ESLint
-- bundles JS and CSS files
-- migrates the built app to the dist folder
-- runs a dev webserver
-- opens your browser at the dev URL
-- reloads the browser upon save

[reactGo](https://github.com/reactGo/reactGo) Your One-Stop solution for a full-stack app with ES6/ES2015 React.js featuring universal Redux, React Router, React Router Redux Hot reloading, CSS modules, Express 4.x, and multiple ORMs

- isomorphic universal Rendering
- Redux Predictive state containers.
- Server-side rendering with React Router 2.x. Having server-side rendering allows you to pre-render the initial state of your components when a user (or search engine crawler) requests a page.
- Integrating Redux with React Router with Redux Simple Router React Router Redux
- Asynchronous Data Fetching on server-side rendering
- Server side authentication + Redirecting for components
- Hot reloading using react-transform-hmr
- Time travel using Redux-Devtools Chrome Extension
- Webpack for both development and production bundles. It's (in my opinion) the best bundler for JS, CSS, LESS, images, and lots more!
- CSS Modules allows for modular and reusable CSS. Say goodbye to conflicts (most of them) and global scope

[react-pwa-reference](https://github.com/localnerve/react-pwa-reference) A project boilerplate and reference example for isomorphic universal reactiflux progressive web applications.
-    Node
-    Express
-    React (Facebook)
-    Fluxible (Yahoo)
-    sw-toolbox, sw-precache (Google)
-    babel6, gulp4, webpack, eslint, mocha/chai, sass

[react-redux-bootstrap-universal-startkerit](https://github.com/mtiger2k/react-redux-bootstrap-universal-startkerit) a product ready starterkit with react redux graphql apollo-client bootstrap universal hot, using mocha, chai, enzyme karma test framework, extracted from reactjsblueprints

[react-redux-starter-kit](https://github.com/cloudmu/react-redux-starter-kit) Enjoy React, Redux, and React-Router, with zero build configuration. This is yet another React and Redux based web application starter kit. However, this one attempts to go beyond the typical simple boilerplates, by showcasing several great technologies (such as React, Redux, React-Router, Bootstrap, Babel, Webpack and JWT) used together to develop a more complex web application, with features such as authentication, navigation, asynchronous data fetching, error handling, caching and pagination, etc.



[react-universally](https://github.com/ctrlplusb/react-universally) A starter kit giving you the minimum requirements for a production ready universal react application.
-    :earth_africa: Server side rendering.
-    :fire: Extreme live development - hot reloading of client/server source as well as your webpack configuration, with high level of error tolerance.
-    :bullettrain_side: express server.
-    :cop: Security on the express server using helmet and hpp.
-    :eyes: react as the view.
-    :twisted_rightwards_arrows: react-router as the router, along with a dynamic routing configuration (i.e. you get code splitting based on your routes).
-    ⛑ react-helmet allowing control of the page title/meta/styles/scripts from within your components. Direct control for your SEO needs.
-    🖌 Very basic CSS support - it's up to you to extend it into CSS Modules, SASS, PostCSS, Aphrodite etc.
-    🏜 Image and Font support.
-    :rocket: Full ES2015 support, using babel to transpile where needed.
-    :package: Bundling of both client and server using webpack v2.
-    :scissors: Client bundle is split by routes.
-    :elephant: Long term caching of the client bundle. Thanks to @mjackson for the inspiration from his super cool web-starter project. Check it out!
-    :leaves: Tree-shaking, supported by webpack.
-    :heavy_check_mark: Type checking via Flow, a beautiful and unobtrusive type framework. NOTE: Flow is a completely optional feature. The flow type annotations get ripped out of the source by the webpack build step. You have no obligation to use flow within your code and can even uninstall the dependency (flow-bin) without breaking the project. I do highly recommend you try it out though.
-    🎛 A development and optimized production configuration.
-    :wrench: Easy environment configuration via dotenv files.
-    :angel: Airbnb's eslint configuration.


[redux-universal-boilerplate](https://github.com/ufocoder/redux-universal-boilerplate) Boilerplate for react universal application building on flux architecture based on redux implementation.Boilerplate based on:
-    ExpressJS
-    React
-    React-router
-    React-helmet
-    React-redux
-    Redux
-    Redial
-    BabelJS
-    Webpack
-    and etc.
-    es6/es7 syntax
-    Testing enviroment
-    Server and client side rendering
-    Routing on client and server sides
-    Hot module replacement
-    Html layout as react component
-    Not Found page with 404 HTTP status
-    Stubs of media asset modules for server bundle

[universal-react](https://github.com/vjamesgarcia/universal-react) react, react native, redux
-    react and react native
-    redux
-    babeljs
-    immutablejs
-    react-router
-   react-router-redux
-    react-intl
-    redux-storage
-    webpack
-    expressjs
-    eslint
-    formatjs Universal internationalization.
-    react-helmet A document head manager for React.
-    webpack-isomorphic-tools
-    chriso/validator.js For simple yet powerfull Este sync/async validation.
-    bluebird Because it's better than native implementation.
-    AVA Futuristic JavaScript test runner.
-    SASS or plain CSS with autoprefixer
-    uuid Generate RFC-compliant UUIDs in JavaScript.
-    react-native-uuid node-uuid for react-native.
-    gulp Aren't NPM scripts better? No.
-    gulp-real-favicon Generate a multiplatform favicon with RealFaviconGenerator
-    react-native-fbsdk For Facebook Login in React Native. Follow the readme install notes.
-    And much more. Explore the repository.


[orthodoxjs](https://github.com/andrew310/orthodoxjs) React / Mobx / Webpack / Express / Material UI / Minimal / Universal Starter. This is meant to be a clean, minimal starting point for universal React apps.


[webpack-library-starter](https://github.com/krasimir/webpack-library-starter) Webpack based boilerplate for producing libraries (Input: ES6, Output: universal library)

[UniversalRelayBoilerplate](https://github.com/codefoundries/UniversalRelayBoilerplate) Boilerplate + examples for React Native (iOS, Android), React (isomorphic, Material-UI), Relay, GraphQL, JWT, Node.js, Apache Cassandra, other databases.

# Yo Generators

[generator-react-webpack](https://github.com/react-webpack-generators/generator-react-webpack)  Yeoman generator for ReactJS and Webpack http://newtriks.com/2013/12/31/automating-react-with-yeoman-and-grunt/  Generator-React-Webpack will help you build new React projects using modern technologies. Out of the box it comes with support for:
-    Webpack
-    ES2015 via Babel-Loader
-    Different supported style languages (sass, scss, less, stylus)
-    Style transformations via PostCSS
-    Automatic code linting via esLint
-    Ability to unit test components via Karma and Mocha/Chai

Generators that extend generator-react-webpack
-    [Generator-React-Webpack-Alt](https://github.com/weblogixx/generator-react-webpack-alt) (Adds ability to create actions, stores and sources for [alt.js](http://alt.js.org/))
-    [Generator-React-Webpack-Redux](https://github.com/stylesuxx/generator-react-webpack-redux) (Adds ability to create actions and reducers for [Redux](https://github.com/rackt/redux))



[generator-react-library](https://github.com/petehunt/generator-react-library) Yeoman generator for React components

[generator-react-gulp-browserify](https://github.com/randylien/generator-react-gulp-browserify) A Yeoman Generator for facebook's React library. It includes gulp, browserify, livereload and famous official Twitter bootstrap Sass version
-    Added watchify support
-    We use browserify extension instead of gulp extension
-    Autorun bower install & npm install by default
-    Gulp
-    Bower
-    jQuery (optional)
-    Browserify
-    Reactify - (removed)
-    Babelify Help to transform JSX (consider to use babelify later)
-    Watchify support! (Sourcemap also!)
-    livereload (BrowserSync)
-    jshintrc file (although eslint is much better)
- To be added - React Bootstrap instead of Sass Bootstrap
-    Sass with Compass
-    Bootstrap - Twitter Bootstrap's official Sass version
-    Modernizr
-    Jade for HTML templates (deprecated used React JSX instead)
-    CoffeeScript for JavaScript (deprecated use React JSX instead)
-    Jest for unit tests


[generator-speedseed](https://github.com/ifedu/generator-speedseed) Oriented to components, allow create/choice template - Multi-Tic-Tac-Toe/TodoMVC - AngularJS/Angular2/jQuery/Polymer/React/VanillaJS - BabelJS/CoffeeScript/TypeScript - Mocha/Jasmine - SaSS/ScSS/LeSS/Stylus - Jade/HTML - Gulp + Yeoman

# Separate Tools and Libs

[Redux Updeep](https://github.com/algolia/redux-updeep) "enforce immutability, update state with little boilerplate" redux-updeep is a small reducer generator that uses updeep to immutably deep merge partial updates into the reducer's state. It's great for reducing boilerplate in your redux actions and reducers!

[Redux Observable](https://github.com/redux-observable/redux-observable) "easily compose anything async with RxJS" RxJS middleware for action side effects in Redux using "Epics" https://redux-observable.js.org - RxJS 5-based middleware for Redux. Compose and cancel async actions to create side effects and more.

[Flow](https://github.com/facebook/flow) "forget about prop types, we want real types" Adds static typing to JavaScript to improve developer productivity and code quality. http://flowtype.org/ **Warning** Flow has a serious defect or faulty design that appears to prevent installation on a Windows computer. Very unprofessional in 2016 to not test a project on the O/S used by 95% of the human population. This project was added based on user-feedback to this list but until this defect is repaired, it's simply not usable.

[React Codemirror](https://github.com/JedWatson/react-codemirror) The excellent CodeMirror editor as a React.js component. Live demo: JedWatson.github.io/react-codemirror

[React Styleguidist](https://github.com/sapegin/react-styleguidist)  React Styleguidist is a style guide generator for React components. It lists component propTypes and shows live, editable usage examples based on Markdown files. You can use it to generate a static HTML page to share and publish or as a workbench for developing new components using hot reloaded dev server. [Check out the demo style guide](http://sapegin.github.io/react-styleguidist/). Based on Webpack, webpack-dev-server and Babel.

[markdown-to-react-components](https://github.com/christianalfoni/markdown-to-react-components) There are several projects that claims to convert markdown using React, but that is not exactly right. They produce one single React component with some plain markdown converted HTML in it. They do not produce React components of the markdown syntax. But this project does!

[React Storybook](https://github.com/kadirahq/react-storybook)  React Storybook is a UI development environment for your React components. With it, you can visualize different states of your UI components and develop them interactively.  React Storybook runs outside of your app. So you can develop UI components in isolation without worrying about app specific dependencies and requirements.  For more information visit: https://getstorybook.io React Storybook also comes with a lot of addons and a great API to customize as you wish. You can also build a static version of your storybook and deploy it anywhere you want.

[component-playground](https://github.com/FormidableLabs/component-playground) A component for rendering React components with editable source and live preview https://formidable.com/open-source/component-playground/


[React Hot Loader](https://github.com/gaearon/react-hot-loader) Tweak React components in real time. http://gaearon.github.io/react-hot-loader/  React Hot Loader 3 is on the horTweak React components in real time. http://gaearon.github.io/react-hot-loader/  izon, and you can try it today (boilerplate branch, upgrade example). It fixes some long-standing issues with both React Hot Loader and React Transform, and is intended as a replacement for both. The docs are not there yet, but they will be added before the final release. For now, this commit is a good reference.

[React Developer Tools](https://github.com/facebook/react-devtools) An extension that allows inspection of React component hierarchy in Chrome Developer Tools. React Developer Tools is a system that allows you to inspect a React Renderer, including the Component hierarchy, props, state, and more. There are shells for Chrome (adding it to the Chrome devtools), Firefox, Atom/Nuclide, and as a standalone Electron app.


[Spectacle Editor](https://github.com/FormidableLabs/spectacle-editor)  Drag and drop Spectacle editor. https://formidable.com/open-source/spectacle-editor/  An Electron based app for creating, editing, saving, and publishing Spectacle presentations. With integrated Plotly support.  This project is a joint effort between Formidable and Plotly. [docs](https://github.com/FormidableLabs/spectacle-editor-docs)

[Structor - visual editor for React components](https://github.com/ipselon/structor)  An advanced visual editor for React components https://helmetrex.com


[React Cosmos](https://github.com/skidding/react-cosmos) DX tool for designing truly encapsulated React components. https://www.youtube.com/watch?v=t9V2oKK83Kg Cosmos scans your project for React components and loads them inside the Component Playground, enabling you to:
- Render your components under any combination of props and state
- See component states evolve in real-time as you interact with running instances
- Working with Cosmos improves the component design because it surfaces any implicit dependencies. It also forces you to define sane inputs for every component, making them more predictable and easier to debug down the road.


[nwb](https://github.com/insin/nwb) Create React apps, components, libraries and other npm modules for use on the web with no configuration (until you need it) nwb provides tooling in a single devDependency for developing, testing and building:
-   React Apps
-    React Components and Libraries
-    npm Modules for the Web

A zero-config development setup is provided for these projects, but nwb also supports configuration and plugin modules which add extra functionality (e.g. Sass support), should you need them

[Live Code Editor](https://github.com/Khan/live-editor) This is the live coding environment developed for the Khan Academy Computer Programming curriculum. It gives learners an editor on the left (either ACE or our Blocks-based drag-and-drop editor) and an output on the right (either JS+ProcessingJS, HTML, or SQL). Here's a tour of how it's used on KA. You can find various demos in the demos/ directory, and start playing immediately with the simple demo:  http://khan.github.io/live-editor/demos/simple/


[Create React App](https://github.com/facebookincubator/create-react-app) Create React apps with no build configuration.
-    [Getting Started](https://github.com/facebookincubator/create-react-app#getting-started) – How to create a new app.
-    [User Guide](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md) – How to develop apps bootstrapped with Create React App.

[create-react-app-now](https://github.com/xkawi/create-react-app-now) Hello, create-react-app, meet Zeit's awesome now.sh service. https://create-react-app.now.sh Deploy React.js Static Web Apps generated with facebookincubator/create-react-app to Zeit's awesome now.sh service. I wrote an article about this project here: [Zero Configuration Deployment for React app with Zeit Now](https://medium.com/@kawixiao/zero-configuration-deployment-for-react-apps-with-zeits-now-4f002be98c#.eyvj3mjdb)

This project is created using [facebookincubator/create-react-app](https://github.com/facebookincubator/create-react-app). Although it supports deployment to github pages and heroku, it does not feel intuitive just yet, as we need to run lots of commands.  This project is specifically to solve just that, with just 1 command: npm run deploy - This is achieved by using Zeit's awesome [now.sh](https://zeit.co/now/) service. It is fast, easy, and intuitive way of deploying your React app.

[JSX to React](https://github.com/delvallejonatan/jsx-to-react)  JSX to React live compiler http://jsxtoreact.host JSX to React live compiler transforms from an XML-like syntax into native JavaScript. XML elements, attributes and children are transformed into arguments that are passed to React.createElement. You don't have to use JSX with React. You can just use plain JS. This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app) and use Babel REPL to compile JSX to React elements.


[tarec](https://github.com/geowarin/tarec) The Awesome REact Cli http://geowarin.github.io/tarec/ Tarec takes care of your React build for you. No more googling and stitching boilerplates together. Just write your application.

[React-designer](https://github.com/fatiherikli/react-designer) Easy to configure, lightweight, editable vector graphics in your react components. http://fatiherikli.github.io/react-designer/  
-    Supports polygon and shape designing (with bezier curves)
-    Implemented default scale, rotate, drag, and arrange actions
-    Custom object types and custom panels
- Examples and demonstration: http://fatiherikli.github.io/react-designer


[Nuclide](https://github.com/facebook/nuclide) An open IDE for web and native mobile development, built on top of Atom http://nuclide.io Nuclide is a collection of features for [Atom](https://atom.io/) to provide IDE-like functionality for a variety of programming languages and technologies. Has [Flow](https://nuclide.io/docs/languages/flow/)


[Atom React Plugin](http://orktes.github.io/atom-react/)



[MediumEditor](https://github.com/yabwe/medium-editor) Medium.com WYSIWYG editor clone. Uses contenteditable API to implement a rich text solution. https://yabwe.github.io/medium-editor/


[Universe Markdown Wysiwyg](https://github.com/cristo-rabani/meteor-universe-react-markdown-wysiwyg)  A few of react components, that providing visual editor of markdown and Html for Meteor https://atmospherejs.com/universe/react-markdown-wysiwyg

[React JS Froala WYSIWYG Editor](https://github.com/froala/react-froala-wysiwyg) React component for Froala WYSIWYG HTML Rich Text Editor. https://froala.com/wysiwyg-editor


[react-json-edito](https://github.com/dustingetz/react-json-editor)  A generic JSON editor, specifically designed for attaching to React state values.

[react-blessed](https://github.com/Yomguithereal/react-blessed) A React custom renderer for the blessed library. This renderer should currently be considered as experimental, is subject to change and will only work with the React's latest version (0.14.x).


[react-blessed-hot-motion](https://github.com/gaearon/react-blessed-hot-motion) This is a demo of a custom [React Blessed](https://github.com/Yomguithereal/react-blessed/) console renderer (warning: very early preview, many things don’t work) using React Motion for animation, and Webpack for listening to code hot updates.

[babel-plugin-react-transform](https://github.com/gaearon/babel-plugin-react-transform/) This Project Is Deprecated  - React Hot Loader 3 is on the horizon, and you can try it today (boilerplate branch, upgrade example). It fixes some long-standing issues with both React Hot Loader and React Transform, and is intended as a replacement for both. The docs are not there yet, but they will be added before the final release. For now, this commit is a good reference.


[atellier](https://github.com/scup/Atellier) The smartest way to share interactive components with your team. http://scup.github.io/atellier/ A React component that works like a preview of other components. An excellent tool to show how your component works and looks with. Easy to install and configure, you can have a router in your project with Atellier and can interact with any component. Imagine a universe in which you may have tools (components) tested in real time! This is amazing!  [Online Demo Atellier and Material UI](http://scup.github.io/atellier/material-ui-atellier/)

# UI Layout

[autoresponsive-react](https://github.com/xudafeng/autoresponsive-react) Auto Responsive Layout Library For React https://xudafeng.github.com/autoresponsive-react

[React Layout Components](https://github.com/rofrischmann/react-layout-components) Useful, Modern and universal layout Components for React.js based on flexbox. The basis <Box> Component is highly inspired by React Native's Flexbox implementation and though accepts almost the same props. It supports all flexbox specifications and automatically adds alternative values and prefixes thanks to inline-style-prefix-all if needed. Note: If you're not familiar with Flexbox at all, I recommend css-tricks ['Complete Guide to Flexbox'](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) which is an awesome source for beginners as well as a nice refreshment for experts.

[React-Grid-Layout](https://github.com/STRML/react-grid-layout) A draggable and resizable grid layout with responsive breakpoints, for React. React-Grid-Layout is a grid layout system much like Packery or Gridster, for React. Unlike those systems, it is responsive and supports breakpoints. Breakpoint layouts can be provided by the user or autogenerated. RGL is React-only and does not require jQuery.

[react-flexbox-grid](https://github.com/roylee0704/react-flexbox-grid) A set of React components implementing flexboxgrid with the power of CSS Modules. http://roylee0704.github.io/react-flexbox-grid/ React-Flexbox-Grid is a set of React components that implement flexboxgrid.css. It's built on top of some the trendiest proposals like CSS Modules (written in SASS), Webpack and ES6. The library harmoniously integrates with your Webpack workflow and it's easily customizable and very flexible.

[react-stonecutter](https://github.com/dantrain/react-stonecutter) Animated grid layout component for React http://dantrain.github.io/react-stonecutter Choose between CSS Transitions or [React-Motion](https://github.com/chenglou/react-motion) for animation.[Demo](http://dantrain.github.io/react-stonecutter) 

[React-flexbox](https://github.com/tcoopman/react-flexbox) Implementation of css flexbox in react with inline styles. It is written in ES6 and requires an ES6 to ES5 transpiler. If there is need for it I can add a transpiled version to the repo.



# UI Component Collections

[react-components](https://github.com/dataminr/react-components) A collection of reusable React components with their own Flux lifecycle.

[Khan Academy React Components](https://github.com/Khan/react-components) Some components we build for Khan Academy that the world might find useful. See http://khan.github.io/react-components/ for a demo and descriptions of the individual components.

[Elemental UI](https://github.com/elementalui/elemental) A flexible and beautiful UI framework for React.js http://elemental-ui.com

[react-ui](https://github.com/Lobos/react-ui) A collection of components for React. http://lobos.github.io/react-ui/

[belle](https://github.com/nikgraf/belle) Configurable React Components with great UX http://nikgraf.github.io/belle/

[React UIkit Components](https://github.com/otissv/react-uikit-components) React UIkit Components for the UIKit CSS framework http://otissv.github.io/react-uikit-components/

[Rebass](https://github.com/jxnblk/rebass) Configurable React Stateless Functional UI Components http://jxnblk.com/rebass  Rebass is a React UI component library that uses inline styles to avoid CSS dependencies and prevent leaky global styles from affecting an application. Rebass components are built as stateless functional components and modeled as presentational components. With unit tests for each component, Rebass is great for prototyping and ready for production.

[Grommet](https://github.com/grommet/grommet) The most advanced UX framework for enterprise applications. https://grommet.github.io

[React-Bootstrap](https://github.com/react-bootstrap/react-bootstrap) Bootstrap 3 components built with React http://react-bootstrap.github.io/

[reactstrap](https://github.com/reactstrap/reactstrap) Simple React Bootstrap 4 components https://reactstrap.github.io

[React-MDL](https://github.com/react-mdl/react-mdl) React Components for Material Design Lite https://react-mdl.github.io/react-mdl/

[react-materialize](https://github.com/react-materialize/react-materialize) Material design for react, powered by [materializecss](https://materializecss.com/) https://react-materialize.github.io/ The main goal of this project is to provide react component for materializecss, at the current stage, I am trying to implement all possible widgets that are supported by materializecss. Please create an issue on github if you find you desired component is not available. There are other material design components for react.js, e.g. material-ui, which is more mature and popular than this one. The main advantage of this project over e.g. material-ui is that it provides a grid system similar to react-bootstrap.

[React Toolbox ](https://github.com/react-toolbox/react-toolbox) A set of React components implementing Google's Material Design specification with the power of CSS Modules http://www.react-toolbox.com  React Toolbox is a set of React components that implement Google's Material Design specification. It's powered by CSS Modules and harmoniously integrates with your webpack workflow, although you can use any other module bundler. You can take a tour through our documentation website and try the components Ilive!

[Material-UI](https://github.com/callemall/material-ui) React Components that Implement Google's Material Design. http://www.material-ui.com

[Essence](https://github.com/Evo-Forge/Essence) Essence - The Essential Material Design Framework http://getessence.io Essence is a CSS framework that implements the guidelines from Google Material Design Specification using Facebook's react.js library. Use it to easily build super-fast and great looking web & mobile interfaces. See [here](http://getessence.io/) what you can build with Essence and how to do it. We've got several examples that will help you get started.

# UI Components Individual

[Griddle](https://github.com/GriddleGriddle/Griddle) Griddle is a simple grid Component for use with React. It depends on Lodash Modules and React.http://griddlegriddle.github.io/Griddle/

[react-datagrid](https://github.com/zippyui/react-datagrid) A carefully crafted DataGrid for React http://zippyui.github.io/react-datagrid

[React Data Grid](https://github.com/adazzle/react-data-grid) Excel-like grid component built with React, with editors, keyboard navigation, copy & paste, and the like http://adazzle.github.io/react-data-grid/

[ReactPivot](https://github.com/davidguttman/react-pivot) React-Pivot is a data-grid component with pivot-table-like functionality for data display, filtering, and exploration. http://davidguttman.github.io/react-pivot/


# A List of Lists

### React Lists of Components
- [React Components Catalog](https://github.com/brillout/awesome-react-components) Dedicated interface at devarchy.com/react-components
- [React Components](https://github.com/sapegin/react-components) "Inspired by the awesome-react-components but lists only the components I use myself and can recommend"
- [React Components](https://github.com/vaffel/react-components) Searchable repository of React-components http://react-components.com/ (Appears to be dead?)
- [React component list](https://github.com/DveMac/react-component-list) NO LONGER MAINTAINED - Check out http://react-components.com/ or https://js.coach/react instead

### React Misc
- [The React List](https://github.com/10UWP/The-React-List) don't you hate people that use "this" everywhere in object programming as if they are completely lost about where their code exists in space and time? Well this entry is this.TheReactList so now I can properly hate myself and be ready for a Woody Allen movie.
- [React Rocks](https://react.rocks/) Pinterst type display of a minor number of React thingies for unknown reasons.
- [Redux Awesome](https://github.com/virtuaone/redux-awesome)
- [React Redux Links](https://github.com/dagman/react-redux-links)
- [React Howto](https://github.com/petehunt/react-howto)
- [React for Beginners](https://github.com/siakaramalegos/react-for-beginners)
- [React Router Tutorial](https://github.com/reactjs/react-router-tutorial)
- [React Native Links](https://github.com/bozzmob/ReactNativeLinks)
- [Web/React Animation Links](https://github.com/firedev/animation)
- [React Examples](https://github.com/mikeperri/react-examples)
- [The Debate Around “Do We Even Need CSS Anymore?”](https://css-tricks.com/the-debate-around-do-we-even-need-css-anymore/)
- [Resources for the React + Meteor + FlowRouter stack](https://github.com/topaztee/JS-stack-resources#real-apps)
- [Cheatsheet for React](http://ricostacruz.com/cheatsheets/react.html)
- [React, Redux, and related tooling](https://github.com/samsch/js-app-learning)
- [React Stack](https://github.com/alagiboy/react-stack)
- [ReactJS-Resources](https://github.com/JonathanZWhite/ReactJS-Resources)
- [react-resources](https://github.com/willklein/react-resources)
- [React/Redux Resources](https://github.com/radiofreemattd/curated-redux-react-resources)
- [React Resources and information](https://github.com/dannyvassallo/react-resources)
- [react-resources](https://github.com/dbertella/react-resources)
- [React Newsletter](http://reactjsnewsletter.com/) weekly newsletter of the best React.js news, articles, projects, and more - brought to you by React.js Program
- [React FAQ](https://github.com/timarney/react-faq)
- [RxJS + React/Flux Libraries](https://github.com/christianramsey/rx-react-flux)
- [React/Redux Links](https://github.com/markerikson/react-redux-links)
- [React-Resources](https://github.com/greggb/React-Resources)
- [Awesome React](https://github.com/enaqx/awesome-react) long list
- [Awesome React Talks](https://github.com/mightyCrow/awesome-react-talks)
- [awesome-react-renderer](https://github.com/chentsulin/awesome-react-renderer)
- [React form Comparison by Example](https://github.com/luqin/react-form-comparison)
- [awesome-functional-reactive](https://github.com/xgrommx/awesome-functional-reactive) sometimes associated with React
- [React Things](https://github.com/ericelliott/react-things)
- [TDD / BDD React.js](https://github.com/Cmdv/Essential-TDD-BDD-React-list) for the Functionally masochistic 
- [Awesome React](https://github.com/syossan27/awesome-react-me) React gets 2 Awesome lists!
- [React in patterns](https://github.com/krasimir/react-in-patterns) List of design patterns/techniques used while developing with React
- [React Learning](https://github.com/ericdouglas/react-learning)
- [Rewrite of React.Parts](https://js.coach/) JS packages, mostly React

### Plain Old Javascript
- [Frontend Development](https://github.com/dypsilon/frontend-dev-bookmarks) "Front End" has got to be the stupidest name of all time, grates on my nerves like fingernails on a blackboard every time I hear it. Essentially "Stupidity in a Bottle" in terms of encapsulating a definition of the programming of computers. But it's a nice long list...
- [Frontend stuff](https://github.com/moklick/frontend-stuff) Yet another name devised by Darth Vader himself...
- [Javascript Must Watch Videos](https://github.com/bolshchikov/js-must-watch) sensible name anyways
- [Awesome Javascript](https://github.com/sorrycc/awesome-javascript) assuming Awesome refers to the list or list maker since applying it to Javascript would create a paradox that could implode the Universe.
- [Essential Javascript Links](https://github.com/ericelliott/essential-javascript-links)


# Editors

First, a list of Javascript and WYSIWYG editors. Then I plan to add notes on React support over time

## Edit 1 - Desktop Javascript Editors

[Adobe Dreamweaver](http://www.adobe.com/products/dreamweaver.html)
- [Emmet for Dreamweaver](https://github.com/emmetio/dreamweaver#readme)

[Brackets](http://brackets.io/)
- [Recommended Brackets Extensions](https://johnpapa.net/my-recommended-brackets-extensions/)
- [Brackets Info](https://www.granneman.com/webdev/editors/brackets/)
- [Emmet plugin for Brackets editor](https://github.com/emmetio/brackets-emmet#readme)

[Aptana Studio](http://www.aptana.com/products/studio3)

[Visual Studio Code](https://code.visualstudio.com/) Visual Studio Code is a streamlined code editor with support for development operations like debugging, task running and version control. It aims to provide just the tools a developer needs for a quick code-build-debug cycle and leaves more complex workflows to fuller featured IDEs.
- [Learning Visual Studio Code](https://johnpapa.net/learning-visual-studio-code/)

[Visual Studio 2015](https://www.visualstudio.com/vs/community/) A fully-featured, extensible, free IDE for creating modern applications for Android, iOS, Windows, as well as web applications and cloud services.

[Light Table](http://lighttable.com/)

[KodeWeave](https://mikethedj4.github.io/kodeWeave/)

[Atom](https://atom.io/)
- [Emmet for Atom](https://github.com/emmetio/emmet-atom#readme)

[WebStorm](https://www.jetbrains.com/webstorm/)

[WeBuilder](http://www.webuilderapp.com/editions.php)

[Firefox Developer Edition](https://www.mozilla.org/en-US/firefox/developer/) 
- [Firefox Developer Tools](https://developer.mozilla.org/en-US/docs/Tools)

[Notepad++](https://notepad-plus-plus.org/)
- [Emmet for Notepad++](https://github.com/emmetio/npp#readme)


## Edit 2 - Online Javascrpt Editors

[SourceLair](https://www.sourcelair.com/home)

[Cloud9](https://c9.io/))

[Codeanywhere](https://codeanywhere.com/)

[ICEcoder](https://icecoder.net/)

[codio](https://codio.com/features/)

[Liveweave](http://liveweave.com/)

[Rendera](http://rendera.herokuapp.com/)

[CodePen](http://codepen.io/#)





## Edit 3 - Desktop WYSIWYG Editors

[Adobe Muse](http://muse.adobe.com/) WEB DESIGN - EASY BREEZY - NO CODE REQUIRED - Complete freeform control, so you can think visually and easily express creative ideas. Your sites will look and behave as intended on all popular browsers and devices. Instant access to your fonts, graphics, photos, vectors, and colors with CC Libraries

[Google Web Designer](https://www.google.com/webdesigner/index.html)  Bring ideas to life across screens - Creae engaging, interactive HTML5-based designs and motion graphics that can run on any device. Let us handle the HTML5 and CSS3 so you’re free to focus on what you love to do: creating gorgeous visual experiences. A full design suite lets you easily bring any vision to life. If you’re feeling more hands-on, all the code behind your designs is hand-editable, so you’re never locked out of your own work. Your ideas are now amplified by code – not restricted by it. Google Web Designer gives you the power to create beautiful, engaging HTML5 content. Use animation and interactive elements to bring your creative vision to life, and enjoy seamless integration with other Google products, like Google Drive, DoubleClick Studio, and AdWords. 

[Xara Web Designer](http://www.magix.com/us/xara-web-designer/) Share your experiences, ideas, or business projects with the world. A few steps is all it takes to easily create your very own website – and there’s no programming skills required. There are tons of templates and design elements to choose from and no restrictive grid system, so your design will always be exactly the way you imagined it.
Over 200 industry-specific website templates Over 600 fonts available Complete design freedom for arranging elements No programming skills required Search engine optimization and web statistics Edit online together with your collaborators, from any device Features for creating and integrating supersites for presentations, flyers etc. Advanced image editing Create your own animations & effects

Over 200 industry-specific website templates Over 600 fonts available Complete design freedom for arranging elements No programming skills required Search engine optimization and web statistics Edit online together with your collaborators, from any device Features for creating and integrating supersites for presentations, flyers etc. Advanced image editing Create your own animations & effects Includes 2,000 MB of web storage and a domain*


[Artiseer](http://www.artisteer.com/) Artisteer - Automated Web Designer - Artisteer is the first and only Web design automation product that instantly creates fantastic looking, unique website templates and blog themes.
-    Design awesome blogs and cool web templates in minutes
-    Export to Blogger, Joomla, Wordpress and other CMS products
-    No need to learn Photoshop, CSS, HTML or other technologies
-    Preview, download and edit online website and template samples!
Artisteer 4.3 - Quick and easy-to-use web design generator for Windows with hundreds of design options and export to WordPress, Joomla, Drupal, DotNetNuke and Blogger. Instantly become a Web Design expert, editing graphics, coding, and creating joomla templates, drupal themes, wordpress themes, DNN skins, and blogger templates all in minutes, without Photoshop or Dreamweaver, and no technical skills.

Themler - Try the most powerful CMS theme designer on the planet. Build themes for your website or for sale. Works directly within your CMS. Create Amazing CMS Themes Without Coding - The most powerful Theme Design Environment that lets you further customize your themes and templates and add advanced features to WordPress, Joomla, Drupal themes. Themler also works with e-commerce systems like Magento, wooCommerce, VirtueMart and PrestaShop! When Artisteer is not enough, export your designs to Themler and continue adding advanced features like transitions and animations, parallax, multiple page templates and more. Now you can master the power of design, no matter how simple or complex!

[WebSite X5](http://www.websitex5.com/en/) One software. No fees. Endless possibilities. WebSite X5 is the best software to create websites saving time and effort. Install the program on your computer and build everything in 5 steps. Create compelling corporate sites, sell online or start your own blog. With WebSite X5 you can even work offline. Anytime, anywhere. At home, on holiday or even on a desert island. You've got all you need to create a professional website on your own without knowing how to code. And no monthly fees. 500 templates. Pick yours. Dozens of ready-to-use free templates that you can customize to suit your needs. Tons of website ideas made to measure for Entrepreneurs, Professionals, Freelance Designers, Photographers, Associations, Online Stores. 


[WYSIWYG Web Builder 11 ](http://wysiwygwebbuilder.com/)
• Visually design your website (What-You-See-Is-What-You-Get).
• No HTML knowledge required! Just drag & drop objects to the page!
• Outputs standard HTML4, HTML5, XHTML, CSS3, PHP.
• Responsive Web Design
• HTML5 Audio/Video, YouTube, Flash Video and more!
• Slidehows, photo galleries, rollover images, rollover text.
• Navigation bars, Menu bar and many other navigation options.

[openElement](http://www.openelement.com/)
-Intuitive interface  ·  Everything is editable
-Managed code  ·  Page layers
-Reusable styles and element packs
-HTML5 & CSS3  ·  Cross-browser
-SEO  ·  Multilingual websites
-Responsive design  ·  Fully customizable CSS
-Element editor - create & share elements
-Easy integration of scripts  ·  Databases
-Image and code optimisation
-Powered by Chromium
-Local webserver for PHP & DB tests

[Pingendo](http://pingendo.com/)  Create quality HTML prototypes quickly, using popular open source tools like Bootstrap, LESS, Fontawesome and more. Work visually and with sources simultaneously, with no need to export. Generate only standard Bootstrap 3.3 HTML and LESS markup.


[Bootstrap Studio](https://bootstrapstudio.io/) Introducing Bootstrap Studio - A powerful desktop app for creating responsive websites using the Bootstrap framework. Bootstrap Studio is a desktop application that helps you create beautiful websites. It comes with a large number of built-in components, which you can drag and drop to assemble responsive web pages. It is built on top of the hugely popular Bootstrap framework, and exports clean and semantic HTML. Thousands of developers and designers use it every day. We are sure you'll love it too! Bootstrap Studio comes with a large number of pretty components for building responsive pages. We've got headers, footers, galleries, slideshows and even basic elements like spans and divs. See some of them below.



## Edit 4 - Online WYSIWYG Editors


[webflow](https://webflow.com/) Design, prototype, and launch dynamic, responsive websites.
All in your browser, without writing code. 

[brix.io](http://brix.io/)  The Best Online Bootstrap Builder & Editor

[StackHive](http://www.stackhive.com/) Quick Responsive Front-End Development In The Browser. StackHive is the most powerful and flexible tool to reduce your front-end development time.

[Weld](https://www.weld.io/) Think it, build it - Build interactive landing pages and websites with custom design, zero code

[BuilderEngine](http://builderengine.com/)  BuilderEngine Website Builder The innovating platform for creating smarter websites. BuilderEngine is the innovating Website Builder for you to create better & smarter websites 

[strikingly](https://www.strikingly.com/)   Make Your Impression Online Create a beautiful website for you & your business, in minutes.
Zero code or design skills required. Trusted by millions of entrepreneurs and creatives - Launching your website has never been easier.

[breezi](http://breezi.com/)

[Cabanova](https://www.cabanova.com/p/en/) Build your best business website ever!

[Dragify](http://dragify.com/)

[SiteCube](http://www.sitecube.com/)

[Wix](http://www.wix.com/) - It All Starts with Your Stunning Website

Wix unites beauty and advanced technology to create your stunning website. It’s easy and free.




