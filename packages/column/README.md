[npm]: https://img.shields.io/npm/v/@jsx-email/column
[npm-url]: https://www.npmjs.com/package/@jsx-email/column

[![npm][npm]][npm-url]
[![Join our Discord](https://img.shields.io/badge/join_our-Discord-5a64ea)](https://discord.gg/FywZN57mTg)
[![libera manifesto](https://img.shields.io/badge/libera-manifesto-lightgrey.svg)](https://liberamanifesto.com)

<div align="center">
	<img src="https://raw.githubusercontent.com/shellscape/jsx-email/main/assets/npm-header.svg" alt="JSX email"><br/><br/>
</div>

# @jsx-email/column

<div>
  <img src="https://raw.githubusercontent.com/shellscape/jsx-email/main/assets/brackets.svg" alt="JSX email" valign="sub">
  A JSX email component which displays columns that separate content bounaries vertically
<div><br>

[`@jsx-email/column` Documentation](https://jsx.email/docs/components/column)

## Requirements

This package requires an [LTS](https://github.com/nodejs/Release) Node version (v18.0.0+) and React v18.2.0+.

## Install

```shell
pnpm add @jsx-email/column

# We recommend pnpm - https://pnpm.io
# But npm and yarn are supported
# npm add @jsx-email/column
# yarn add @jsx-email/column
```

## Usage

We recommend using the [`@jsx-email/cli`](../cli) for [creating new templates](https://jsx.email/docs/quick-start#create-a-template).

Create an email template file (e.g. `Email.tsx`) and import the component:

```jsx
import { Row } from '@jsx-email/row';
import { Column } from '@jsx-email/column';
const Email = () => {
  return(
    <Row>
      <Column>A<Column/>
      <Column>B<Column/>
      <Column>C<Column/>
    </Row>
  );
};
```

Please see the [`@jsx-email/column` Documentation](https://jsx.email/docs/components/column) for props and additional usage information.

## Attribution 🧡

This package was built upon prior work for `react-email` by Bu Kinoshita ([@bukinoshita](https://twitter.com/bukinoshita)) and Zeno Rocha ([@zenorocha](https://twitter.com/zenorocha)).

## License

[MIT License](./LICENSE.md)
