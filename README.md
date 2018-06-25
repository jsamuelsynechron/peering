# Peer Rating Server

## What is this?

Node JS based API server and manager for Peer App.

## Quick intro
Deploy



### [Why this starter uses `react-semantic-ui`?](/docs/SUI.md)
> SPOILER: because SUI and SUIR are awesome

You're always free to use any other UI framework with `suicrux`.
**[UI framework comparison here.](https://hackernoon.com/the-coolest-react-ui-frameworks-for-your-new-react-app-ad699fffd651)**

## What's inside?


[![bitHound Dependencies](https://www.bithound.io/github/Metnew/suicrux/badges/dependencies.svg)](https://www.bithound.io/github/Metnew/suicrux/master/dependencies/npm) [![bitHound Dev Dependencies](https://www.bithound.io/github/Metnew/suicrux/badges/devDependencies.svg)](https://www.bithound.io/github/Metnew/suicrux/master/dependencies/npm)

### Client:

- **[React 16](https://facebook.github.io/react/)** and **[Redux](http://redux.js.org/)**
- **SASS**, **[PostCSS](https://github.com/postcss/postcss)**, and **[styled-components](https://github.com/styled-components/styled-components)** support.
- **[React-Router v4](https://github.com/ReactTraining/react-router)** + **[React-Router-Redux v5](https://github.com/reactjs/react-router-redux)**
- **[Redux-thunk](https://github.com/gaearon/redux-thunk)**, **[Redux-Devtools-Extension](https://github.com/zalmoxisus/redux-devtools-extension)**
- **[Fetch polyfill](https://github.com/matthew-andrews/isomorphic-fetch)**
- **[Semantic-ui-react](http://react.semantic-ui.com/)** - UI components.
- **[Store2](https://github.com/nbubna/store)** and **[js-cookie](https://github.com/js-cookie/js-cookie)** - LocalStorage and cookies.
- **[Lodash](https://lodash.com/)** - is a dependency of SUIR.
- **[react-async-component](https://github.com/ctrlplusb/react-async-component)** - library for lazy-loading
- **[react-ga](https://github.com/react-ga/react-ga)** - advanced Google Analytics for React
- **[react-intl](https://github.com/yahoo/react-intl)** - i18n.
- **[immutable](https://facebook.github.io/immutable-js/)**, **[reselect](https://github.com/reactjs/reselect)** and **[normalizr](https://github.com/paularmstrong/normalizr)**


### Build (Webpack):

Based on [`tiny-universal-skeleton`](https://github.com/Metnew/tiny-universal-skeleton) and includes:

- Latest Webpack
- Babel: `stage-1` and few cool plugins for development and production.
- **HMR**, hotMiddleware,
- Check your code with **[Eslint](https://github.com/eslint/eslint)** and **[Stylelint](https://github.com/stylelint/stylelint)** (that you can uncomment inside `postcss.config.js`)
- **[Offline-plugin](https://github.com/NekR/offline-plugin)**
- **[favicons-webpack-plugin](https://github.com/jantimon/favicons-webpack-plugin)**
- **[webpack-bundle-analyzer](https://www.npmjs.com/package/webpack-bundle-analyzer)**
- **[compression-webpack-plugin](https://github.com/webpack-contrib/compression-webpack-plugin)**
- **[optimize-css-assets-webpack-plugin](https://github.com/NMFR/optimize-css-assets-webpack-plugin)**
- **[autodll-webpack-plugin](https://github.com/asfktz/autodll-webpack-plugin)**
- **[assets-webpack-plugin](https://github.com/kossnocorp/assets-webpack-plugin)**
- **[optimize-js-plugin](https://github.com/vigneshshanmugam/optimize-js-plugin)**
- **[wepback-assets-manifest](https://www.npmjs.com/package/webpack-assets-manifest)**
- **[circular-dependency-plugin](https://github.com/aackerman/circular-dependency-plugin)**
- **[extract-text-webpack-plugin](https://github.com/webpack-contrib/extract-text-webpack-plugin)**

### Server:

- **[morgan](https://www.npmjs.com/package/morgan)** - request logger middleware.
- **[helmet](https://github.com/helmetjs/helmet)** - secure your Express app.
- **[cookie-parser](https://www.npmjs.com/package/cookie-parser)** - cookie parsing middleware.
- **[body-parser](https://github.com/expressjs/body-parser)** - body parsing middleware
- **[compression](https://github.com/expressjs/compression)** - compression middleware (gzip).
- **[jsonwebtoken](https://github.com/auth0/node-jsonwebtoken)** - JWT ~~for the win~~.
- **[raven](https://docs.sentry.io/clients/node/)** - Sentry for Node

### Other:

- **[Jest](https://facebook.github.io/jest/)** - awesome testing framework..
- [And more tools for building and testing...](https://github.com/Metnew/suicrux/blob/master/package.json)

## Usage

### How it works?

"30-seconds guide":
```bash
  # Install
  git clone --depth=1 https://github.com/Metnew/suicrux.git
  cd suicrux
  npm install
  # Development
  npm run dev
  # Build
  npm run build
  # Production
  npm run start
```

More detailed:

#### **[v1.0.0 Release notes](https://github.com/Metnew/suicrux/releases/tag/v1.0.0)** - most detailed description of the latest changes

#### **[Most commonly asked questions are here.](/docs/faq.md)**

#### [Webpack configuration](/docs/webpack.md)

#### [Available scripts](/docs/scripts.md)

#### [How does i18n work?](/docs/i18n.md)

#### [Testing](/docs/testing.md)

#### [Why does this starter use `react-semantic-ui`?](/docs/SUI.md)

#### [Environment variables and configuration.](/docs/env_vars.md)

#### ~~[Starter architecture and design. (not finished)](/docs/design.md)~~

### Nearest future:

- CLI app
- Redux code-splitting

### Something very important:

> Have a question? Ask! :wink:

Any help is highly appreciated. PRs, issues, questions, enhancements are always welcome.

### Author

Vladimir Metnew [vladimirmetnew@gmail.com](mailto:vladimirmetnew@gmail.com)

### LICENSE

Apache License 2.0
