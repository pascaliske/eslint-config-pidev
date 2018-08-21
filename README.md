# Shareable ESLint Config for PI-Webdesign

[![Greenkeeper badge](https://badges.greenkeeper.io/pascaliske/eslint-config-pidev.svg)](https://greenkeeper.io/)

Shareable eslint config for the PI-Webdesign projects.

## Install

First install all needed dependencies:

```bash
yarn add babel-eslint eslint eslint-plugin-ava eslint-plugin-jsdoc --dev
```

Then install the shareable config itself:

```bash
yarn add eslint-config-pidev --dev
```

## Usage

The eslint shareable configs can be used with the `extends` feature of `.eslintrc` files.

Learn more about [shareable configs](http://eslint.org/docs/developer-guide/shareable-configs) on the official ESLint website.

To use the shareable config, first install it and then, add this to your .eslintrc.yml file:

```yml
extends: pidev
parser: babel-eslint
plugins:
  - ava
  - jsdoc
```

*Note: You can omit the `eslint-config-` prefix since it is automatically assumed by ESLint.*

You can override settings from the shareable config by adding them directly into your
`.eslintrc.yml` file.

## Learn more

For the full listing of rules visit the [wiki](https://github.com/pascaliske/eslint-config-pidev/wiki).

## License

MIT. Copyright &copy; [Pascal Iske](https://pascal-iske.de).
