# eslint-config-smartcare

This package includes the shareable ESLint configuration used by Smartcare.

## Usage

Get a list of the peerDependency requirements:

```sh
npm info "eslint-config-smartcare@latest" peerDependencies
```

For each peer dependency:

```sh
yarn add --dev <dependency>@<version>
```

Install this package:

```sh
yarn add --dev eslint-config-smartcare
```

Then create a file named `.eslintrc.js` with the following contents in the root folder of your project:

```js
{
  "extends": "@smartcare/eslint-config-smartcare"
}
```
