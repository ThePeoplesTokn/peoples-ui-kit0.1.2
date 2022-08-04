#  Peoples UIkit



Peoples UIkit is a set of React components and hooks used to build pages on Peoples' apps. It also contains a theme file for dark and light mode.

## Install

`yarn add peoples-ui-kit`

## Setup

### Theme

Before using Peoples UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from 'peoples-ui-kit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@pancakeswap-libs/uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.


