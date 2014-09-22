# CSS WIDOWS

  Mobile-first classes for css-widows.
  Set the desired css-widows on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-widows
```
View on [npm](https://www.npmjs.org/package/css-widows)


## File Size

607B widows.css
458B widows.min.css 
164B minified and gzipped

## The Code
```
.widow0 { widows: 0; }
.widow2 { widows: 2; }
.widow3 { widows: 3; }
.widowi { widows: inherit; }

@media screen and (min-width: 48em) {
  .widow0-ns { widows: 0; }
  .widow2-ns { widows: 2; }
  .widow3-ns { widows: 3; }
  .widowi-ns { widows: inherit; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .widow0-m { widows: 0; }
  .widow2-m { widows: 2; }
  .widow3-m { widows: 3; }
  .widowi-m { widows: inherit; }
}

@media screen and (min-width: 64em)  {
  .widow0-l { widows: 0; }
  .widow2-l { widows: 2; }
  .widow3-l { widows: 3; }
  .widowi-l { widows: inherit; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

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

