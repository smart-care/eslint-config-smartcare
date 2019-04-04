# eslint-config-smartcare

This package includes the shareable ESLint configuration used by Smartcare.

## Requirements

To see a list of the peer dependency requires run:

```sh
npm info "eslint-config-smartcare@latest" peerDependencies
```

## Install

Run the following command:

```sh
npx install-peerdeps --dev @smartcare/eslint-config-smartcare
```

Don't worry if you are using Yarn `install-peerdeps` will work with Yarn.

Then create a file named `.eslintrc.js` with the following contents in the root folder of your project:

```js
{
  "extends": "@smartcare/eslint-config-smartcare"
}
```

For the Prettier config create a file named `prettier.config.js` with the following contents in the root folder of your project:

```js
module.exports = require('@smartcare/eslint-config-smartcare/prettier.config');
```
