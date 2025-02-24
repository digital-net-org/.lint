<h1>
    <img width="300" src="https://raw.githubusercontent.com/digital-net-org/.github/refs/heads/master/assets/logo_v2025.svg">
</h1>
<div justify="center">
    <a href="https://dotnet.microsoft.com/en-us/"><img src="https://img.shields.io/badge/Typescript-blue.svg"></a>
</div>
<p>
    <em>@digital-net-org/.lint</em>
</p>
<p>
    ESLint/Prettier configuration for Digital.net JS/TS projects.
</p>

## Installation

#### Install .lint
```
npm i -D github:digital-net-org/lint
```
#### Install peer dependencies
```
npm i -D eslint prettier typescript-eslint @eslint/js eslint-plugin-import eslint-config-prettier eslint-plugin-react eslint-plugin-react-hooks
```

## Usage
#### Eslint
Create a `eslint.config.mjs` file in the root of your project and add the following code:
```js
import { eslintDigitalConfig } from 'digital-lint';
export default eslintDigitalConfig;
```

#### Prettier
Create a `prettier.config.mjs` file in the root of your project and add the following code:
```js
import { prettierDigitalConfig } from 'digital-lint';
export default prettierDigitalConfig;
```
