# css-widows 0.0.6

Css module of single purpose classes for widows

#### Stats

186 | 16 | 16
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-widows
```

#### With Git

```
git clone https://github.com/tachyons-css/css-widows
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-widows";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-widows">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   WIDOWS
*/
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
@media screen and (min-width:48em) and (max-width: 64em) {
 .widow0-m { widows: 0; }
 .widow2-m { widows: 2; }
 .widow3-m { widows: 3; }
 .widowi-m { widows: inherit; }
}
@media screen and (min-width: 64em) {
 .widow0-l { widows: 0; }
 .widow2-l { widows: 2; }
 .widow3-l { widows: 3; }
 .widowi-l { widows: inherit; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC
