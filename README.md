*This repository is a mirror of the [component](http://component.io) module [reinpk/zeroes](http://github.com/reinpk/zeroes). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/reinpk-zeroes`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# zeroes

Zeroes array utility

## Installation

    $ component install reinpk/zeroes

## API

### zeroes(dimensions)

Create an array full of zeroes:

```js
zeroes(5); // returns [0, 0, 0, 0, 0]
```

Create a matrix full of zeroes:

```js
zeroes([2, 2]); // returns [ [0, 0], [0, 0] ]
zeroes([2, 2, 2]); // returns [ [ [0, 0], [0, 0] ], [ [0, 0], [0, 0] ]
```

You can also pass in an alternate initial value, if you desire:
```js
zeroes(3, 1); // returns [1, 1, 1]
zeroes(3, { a : 1 }); // returns [{ a : 1 }, { a : 1 }, { a : 1 }]
```


## License

    WWWWWW||WWWWWW
     W W W||W W W
          ||
        ( OO )__________
         /  |           \
        /o o|    MIT     \
        \___/||_||__||_|| *
             || ||  || ||
            _||_|| _||_||
           (__|__|(__|__|

Copyright (C) 2013 Peter Reinhardt

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
