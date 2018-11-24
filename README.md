# [DEPRECATED] parcel-plugin-react-svg [![Build Status](https://travis-ci.org/restlessbit/parcel-plugin-react-svg.svg?branch=master)](https://travis-ci.org/restlessbit/parcel-plugin-react-svg)

**This package has been deprecated in favor of the [official SVGR package](https://github.com/smooth-code/svgr/tree/master/packages/parcel-plugin-svgr).**

Parcel plugin for using SVGs as React components.

```jsx
import React from 'react'
import BusteloIllo from './bustelo.svg'

class App extends React.Component {
  render() {
    return <BusteloIllo width={500} fill="blue" />
  }
}
```

## How to use it

Install `parcel-plugin-react-svg` from npm and you should be all good to go 💫.

With npm:

```bash
npm install parcel-plugin-react-svg -D
```

Or if you prefer yarn:

```bash
yarn add parcel-plugin-react-svg -D
```
