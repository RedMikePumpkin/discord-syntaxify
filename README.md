# discord-syntaxify

Turn any text into weird discord formatting

You can see a live demo [here](http://redmikepumpkin.github.io/discord-syntaxify/index.html)

## files

`LICENSE` - License (MIT)

`README.md` - This

`syntaxify.js` - a JS library for syntaxifying text

`syntaxify.html` - a simple HTML file that shows off `syntaxify.js`

`index.html` - a file that redirects to `syntaxify.html`

## `syntaxify.js` docs

### `Syntaxify()`

Parameters:

- <`String`> text: text to be syntaxified

Returns: <`String`>: the syntaxified text, will be "Error!" if an error occured

Example:

```js
// include syntaxify.js in your html code

var string = "Yeet!";

var syntaxified = Syntaxify(string);

console.log(syntaxified);
// output expected:
// "||**~~__*`Y`*__~~**||||**~~__*`e`*__~~**||||**~~__*`e`*__~~**||||**~~__*`t`*__~~**||||**~~__*`!`*__~~**||"
```
