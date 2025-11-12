# DEX  ui-sdk

[![Version](https://img.shields.io/npm/v/@ndex/ui-sdk)](https://www.npmjs.com/package/@ndex/ui-sdk) [![Size](https://img.shields.io/bundlephobia/min/@ndex/ui-sdk)](https://www.npmjs.com/package/@ndex/ui-sdk)

@ndex/ui-sdk is a set of React components and hooks used to build pages on DEX apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @ndex/ui-sdk`

## Setup

### Theme

Before using @ndex/ui-sdk, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@ndex/ui-sdk'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@ndex/ui-sdk'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.

## How to use the UIkit

If you want to use components from the UIkit, check the [Storybook documentation](https://github.com/bitbd83/ndex-ui-sdk/)
