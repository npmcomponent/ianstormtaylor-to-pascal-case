*This repository is a mirror of the [component](http://component.io) module [ianstormtaylor/to-pascal-case](http://github.com/ianstormtaylor/to-pascal-case). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ianstormtaylor-to-pascal-case`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# to-pascal-case

  Convert a string to pascal case.

## Installation

    $ component install ianstormtaylor/to-pascal-case
    $ npm install to-pascal-case

## Example

```js
var pascal = require('to-pascal-case');

pascal('space case'); // "SpaceCase"
pascal('snake_case'); // "SnakeCase"
pascal('dot.case');   // "DotCase"
pascal('weird[case'); // "WeirdCase"
```

## API

### toCamelCase(string)
  
  Returns the pascal-case variant of a `string`.

## License

  MIT
