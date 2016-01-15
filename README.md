# css-hyphens 0.0.6

Css module of single purpose classes for hyphens

#### Stats

181 | 12 | 12
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-hyphens
```

#### With Git

```
git clone https://github.com/tachyons-css/css-hyphens
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-hyphens";
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
<link rel="stylesheet" href="path/to/module/css/css-hyphens">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   HYPHENS
*/
.hyphen-none { hyphens: none; }
.hyphen-manual { hyphens: manual; }
.hyphen-auto { hyphens: auto; }
@media screen and (min-width: 48em) {
 .hyphen-none-ns { hyphens: none; }
 .hyphen-manual-ns { hyphens: manual; }
 .hyphen-auto-ns { hyphens: auto; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .hyphen-none-m { hyphens: none; }
 .hyphen-manual-m { hyphens: manual; }
 .hyphen-auto-m { hyphens: auto; }
}
@media screen and (min-width: 64em) {
 .hyphen-none-l { hyphens: none; }
 .hyphen-manual-l { hyphens: manual; }
 .hyphen-auto-l { hyphens: auto; }
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

MIT

