babel-preset-metal
===================================

A babel preset for building Metal.js projects.

## Usage

This is a [babel preset](http://babeljs.io/docs/plugins/) that provides a default configuration for building Metal.js projects with babel. Even though everything added here is optional (except perhaps babel-preset-es2015), still they're useful. To use this, just add it to your package.json and pass it as a preset when calling babel:

```javascript
{
  "preset": ["metal"]
}
```

## Included

### Plugins

* [babel-plugin-metal-register-components](https://github.com/mairatma/babel-plugin-metal-register-components)

### Presets

* [babel-preset-es2015](https://www.npmjs.com/package/babel-preset-es2015)

### Others

* `resolveModuleSource` is set to a function that converts aliased bower component imports (using the **bower:** prefix) to real paths.
