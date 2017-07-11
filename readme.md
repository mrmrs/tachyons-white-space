# tachyons-white-space 4.0.6

Tachyons css module for setting white space across breakpoints.

#### Stats

185 | 12 | 12
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-white-space
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/tachyons-white-space
```

ssh:
```
git clone git@github.com:tachyons-css/tachyons-white-space.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-white-space";
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
<link rel="stylesheet" href="http://unpkg.com/tachyons-white-space@4.0.6/css/tachyons-white-space.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/tachyons-white-space">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*

   WHITE SPACE

*/
.ws-normal { white-space: normal; }
.nowrap { white-space: nowrap; }
.pre { white-space: pre; }
@media screen and (min-width: 30em) {
 .ws-normal-ns { white-space: normal; }
 .nowrap-ns { white-space: nowrap; }
 .pre-ns { white-space: pre; }
}
@media screen and (min-width: 30em) and (max-width: 60em) {
 .ws-normal-m { white-space: normal; }
 .nowrap-m { white-space: nowrap; }
 .pre-m { white-space: pre; }
}
@media screen and (min-width: 60em) {
 .ws-normal-l { white-space: normal; }
 .nowrap-l { white-space: nowrap; }
 .pre-l { white-space: pre; }
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

