*This repository is a mirror of the [component](http://component.io) module [yields/delay](http://github.com/yields/delay). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/yields-delay`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# delay

  delay the given `fn`.

## Installation

    $ component install yields/delay

## Example

```js
var el = document.querySelector('#search');
var delay = require('delay');
el.onkeyup = delay(200, function(e){
  var val = e.target.value;
  // do ajax search or something.
});
```

## License

  MIT
