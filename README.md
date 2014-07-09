# CSS WIDOWS

  Mobile-first classes for css-widows.
  Set the desired css-widows on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-widows
```
or download the css on github and include in your project.

## File Size


## The Code
```
.widow0 { widows: 0; }
.widow2 { widows: 2; }
.widow3 { widows: 3; }
.widowi { widows: inherit; }

@include break(not-small) {
  .widow0-ns { widows: 0; }
  .widow2-ns { widows: 2; }
  .widow3-ns { widows: 3; }
  .widowi-ns { widows: inherit; }
}

@include break(medium) {
  .widow0-m { widows: 0; }
  .widow2-m { widows: 2; }
  .widow3-m { widows: 3; }
  .widowi-m { widows: inherit; }
}

@include break(large) {
  .widow0-l { widows: 0; }
  .widow2-l { widows: 2; }
  .widow3-l { widows: 3; }
  .widowi-l { widows: inherit; }
}

```

## Author

[http://mrmrs.cc](http://mrmrs.cc - Entire internet gateway to all things mrmrs)
[http://mrmrs.io](http://mrmrs.io - Open source projects)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

