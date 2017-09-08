# eslint-config-smartcare

This package includes the shareable ESLint configuration used by Smartcare.

## Usage

First, install this package, ESlint and the necessary plugins.

```sh
yarn add -D @smartcare/eslint-config-smartcare babel-eslint@^7.2.3 eslint@^4.6.1 eslint-config-airbnb@^15.1.0 eslint-config-prettier@^2.4.0 eslint-plugin-flowtype@^2.35.1 eslint-plugin-import@^2.7.0 eslint-plugin-jsx-a11y@^5.1.1 eslint-plugin-prettier@^2.2.0 eslint-plugin-react@^7.3.0 prettier@^1.6.1
```

Then create a file named `.eslintrc` with the following contents in the root folder of your project:

```js
{
  "extends": "smartcare"
}
```
