# Webpack Starter

Ready-to-use webpack starter including:

- [webpack](https://webpack.js.org)
- [Babel](https://babeljs.io) with [the latest preset](https://babeljs.io/docs/en/babel-preset-env)
- [ESLint](https://eslint.org)
- [Sass](http://sass-lang.com) with [stylelint](https://stylelint.io) and hot reloading
- [HtmlWebpackPlugin](https://webpack.js.org/plugins/html-webpack-plugin)

And other useful loaders and linters.

## Usage

Clone the repository to your computer. You must have [Node.js](https://nodejs.org) (> v4) and [Yarn](https://yarnpkg.com/lang/en/docs/install) installed:

```bash
git clone git@github.com:gabrielecanepa/webpack-starter.git my-project
# or `gh repo clone gabrielecanepa/webpack-starter my-project`

cd my-project

# Install packages and run the app
yarn setup
```

### Scripts

Some scripts are already provided in your `package.json`.

To start a local server on port `8080`:

```bash
yarn start
# or in development mode
yarn dev
```

To lint all your JavaScript and CSS/SCSS files:

```bash
yarn lint
```

To build the static files:

```bash
yarn build
```
