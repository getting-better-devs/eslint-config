![ESLint Logo](https://blog.geekhunter.com.br/wp-content/uploads/2020/11/eslint.png)

# Getting Better Eslint Configuration

This repository contains the ESLint configuration file for the "Getting Better" organization. This configuration is designed to enforce a consistent code style and catch potential errors or issues in JavaScript and TypeScript code.

## Installation

To use this ESLint configuration, you can install it as a dev dependency in your project:

```shell
npm i eslint-config-getting-better -D
```

## Usage

Create an `.eslintrc.json` file in the root of your project and just extend the configuration into it:

```json
{
  "extends": "eslint-config-getting-better"
}
```
