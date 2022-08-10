# os in React Native

node's [os](https://nodejs.org/api/os.html) API in React Native

This module is used by [Peel](http://www.peel.com/)

## Install

- Create a new react-native project. [Check react-native getting started](http://facebook.github.io/react-native/docs/getting-started.html#content)

- In your project dir:

```
npm install @ahsanihsan/react-native-os --save
```

**Note for iOS:** If your react-native version < 0.40 install with this tag instead:

```
npm install @ahsanihsan/react-native-os@1.0.3 --save
```

## Link in the native dependency

```
react-native link @ahsanihsan/react-native-os
```

**_Step 3 Profit_**

## Usage

### package.json

_only if you want to write require('os') in your javascript_

```json
{
  "react-native": {
    "os": "react-native-os"
  }
}
```

## Support for react native 0.69

This package is a fork of [aprock](https://github.com/aprock/react-native-os) and it adds support for react native versions that enable fabric architecture

## Contributors

[Andy Prock](https://github.com/aprock)
[Ahsan Ihsan](https://github.com/ahsanihsan)

PR's welcome!
