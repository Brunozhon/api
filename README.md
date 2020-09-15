# API (api)

API for brunozhon.github.io

# API intro

The API is a way that **brunozhon.github.io could interact with you**.

Like this:

Server file `api.js`

```javascript
function heaxfy(str) {
  return str.toString(16)
}
```

Client file `clientdemo.js`

```javascript
import 'api.js';
console.log(hexafy("Hello, world!"));
```

This demo is in JavaScript, but you can use it in CoffeeScript or other programming languge!

CoffeeScript:

```coffeescript
hexafy = (str) ->
  return str.toString 16
  
console.log hexafy "Hello, world!"
```

### JavaScript vs. CoffeeScript vs. VBScript

|Example|JavaScript|CoffeeScript|VBScript|
|-------|----------|------------|--------|
|Count through all six headings in HTML|:white_check_mark:|:white_check_mark:|:white_check_mark:|
|Async functions|:white_check_mark:|:white_check_mark:|:x:|
|Two kinds of functions|:white_check_mark:|:x:|:white_check_mark:|
|Add, subtract, multiply...|:white_check_mark:|:+1:|:x:|
|`toString()` heaxafy, banaryfy,...|:white_check_mark:|:white_check_mark:|:x:|
|Extra sublangnges|:white_check_mark:|:-1:|:-1:|

So which do you use for your API

> *"It depends of the type*
> *of API youre using"*
> \- Unknown 
