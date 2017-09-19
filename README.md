# eslint-config-smartcare

This package includes the shareable ESLint configuration used by Smartcare.

## Usage

First, install this package, ESlint and the necessary plugins.

```sh
yarn add -D @smartcare/eslint-config-smartcare babel-eslint@^8.0.0 eslint@^4.7.1 eslint-config-airbnb@^15.1.0 eslint-config-prettier@^2.5.0 eslint-plugin-flowtype@^2.35.1 eslint-plugin-import@^2.7.0 eslint-plugin-jsx-a11y@^5.1.1 eslint-plugin-prettier@^2.3.1 eslint-plugin-react@^7.3.0 prettier@^1.7.0
```

Then create a file named `.eslintrc` with the following contents in the root folder of your project:

```js
{
  "extends": "@smartcare/eslint-config-smartcare"
}
```
