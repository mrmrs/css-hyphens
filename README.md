# css-hyphens 1.0.6

Css module of single purpose classes for hyphens

#### Stats

210 | 12 | 36
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-hyphens
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-hyphens
```

ssh:
```
git clone git@github.com:tachyons-css/css-hyphens.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-hyphens";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-hyphens@1.0.6/css/css-hyphens.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-hyphens">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   HYPHENS
*/
.hyphen-none { -webkit-hyphens: none; -ms-hyphens: none; hyphens: none; }
.hyphen-manual { -webkit-hyphens: manual; -ms-hyphens: manual; hyphens: manual; }
.hyphen-auto { -webkit-hyphens: auto; -ms-hyphens: auto; hyphens: auto; }
@media screen and (min-width: 48em) {
 .hyphen-none-ns { -webkit-hyphens: none; -ms-hyphens: none; hyphens: none; }
 .hyphen-manual-ns { -webkit-hyphens: manual; -ms-hyphens: manual; hyphens: manual; }
 .hyphen-auto-ns { -webkit-hyphens: auto; -ms-hyphens: auto; hyphens: auto; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .hyphen-none-m { -webkit-hyphens: none; -ms-hyphens: none; hyphens: none; }
 .hyphen-manual-m { -webkit-hyphens: manual; -ms-hyphens: manual; hyphens: manual; }
 .hyphen-auto-m { -webkit-hyphens: auto; -ms-hyphens: auto; hyphens: auto; }
}
@media screen and (min-width: 64em) {
 .hyphen-none-l { -webkit-hyphens: none; -ms-hyphens: none; hyphens: none; }
 .hyphen-manual-l { -webkit-hyphens: manual; -ms-hyphens: manual; hyphens: manual; }
 .hyphen-auto-l { -webkit-hyphens: auto; -ms-hyphens: auto; hyphens: auto; }
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

