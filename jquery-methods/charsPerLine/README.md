# .charsPerLine()

## About

This function returns an array of values where each value represents a line in the textarea.  Each value contains an object with some properties for each line.  The plugin handles both line breaks using `\n\r` and word wrapping where no line breaks occur.

* __string__ - the actual string on that line.
* __num__ - the number of characters on that line.
* __numTotal - the number of characters on that line including previous lines.

The lines will be in order so index `0` is line number `1`.

## Examples

```js
$('#textarea-elem').charsPerLine();
```

## Author

[Websanova](http://websanova.com) - JavaScript Plugin Development