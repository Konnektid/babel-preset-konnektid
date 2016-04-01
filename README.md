# babel-preset-konnektid

This preset combines the presets and/or plugins that we frequently use at [Konnektid](https://konnektid.com). Using this preset enables you to use [most ES6 and ES7 features](#available-language-features), allowing for (hopefully) cleaner and easier to write JavaScript. Note that [some features](#unavailable-at-this-time) are not available to use at this time, as they are still in active development and therefore likely to change.

## Available language features
This preset includes the `React`, `ES2015` and `Stage 1` presets. This means the following features are available:

### React
  - JSX syntax
  - Flow syntax

### ES2015
  - Template literals
  - Literals
  - Function name
  - Arrow functions
  - Block scoped functions
  - Classes
  - Object super
  - Shorthand properties
  - Computed properties
  - Duplicate keys
  - For...of
  - Sticky regex
  - Unicode regex
  - Constants
  - Spread
  - Parameters
  - Destructuring
  - Block scoping
  - Typeof symbol
  - Modules CommonJS
  - Generator

### Stage 3
  - Async
  - Exponentiation operator


### Stage 2
  - Trailing function commas
  - Object rest Spread

### Stage 1
  - Class constructor call
  - Class properties
  - Export extensions

## Unavailable at this time
  - Decorators (*Stage 1* - pending proposal update)
  - Do expressions (*Stage 0*)
  - Function bind (*Stage 0*)
