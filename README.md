# DEX  @web3react/ui-sdk

[![Version](https://img.shields.io/npm/v/@web3react/ui-sdk)](https://www.npmjs.com/package/@web3react/ui-sdk) [![Size](https://img.shields.io/bundlephobia/min/@web3react/ui-sdk)](https://www.npmjs.com/package/@web3react/ui-sdk)

@web3react/ui-sdk is a set of React components and hooks used to build pages on DEX apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @web3react/ui-sdk`

## Setup

### Theme

Before using @web3react/ui-sdk, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@web3react/ui-sdk'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@web3react/ui-sdk'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.

## How to use the UIkit

If you want to use components from the UIkit, check the [Storybook documentation](https://github.com/cheeseswapbsc/web3react-ui-sdk)
