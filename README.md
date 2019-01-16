# react-matrix-effect [![npm][npm-image]][npm-url]

[npm-image]: https://img.shields.io/npm/v/react-matrix-effect.svg
[npm-url]: https://www.npmjs.com/package/react-matrix-effect


<p align="center">react-matrix-effect provides a Matrix React component for a movie-like animation.</p>

<p align="center">
  <img src="https://www.sadkit.com/assets/img/react-matrix-effect.jpg" alt="Matrix Effect Screenshot" width="640px" height="480px" />
</p>

## Installation

In order to use the component, you will have to install it first via npm:

```
npm install --save react-matrix-effect 
```

## Usage

Then, import it in your React app:

```javascript
import Matrix from 'react-matrix-effect';
```

Now you can use the component directly inside your Babel HTML template:

```html
<Matrix/>
```

## Options

You may also pass some options to the component:
* ***width*** for the canvas width (*number*)
* ***height*** for the canvas height (*number*)
* ***fullscreen*** (*boolean*, overrides width and height)
* ***colSize*** (*number*, width of a column)
* ***fontSize*** (*number*, font size in pixels)
* ***color*** (*string*, hex font color)
* ***frequency*** (*number*, float describing frequency of the characters)
* ***speed*** (*number*)
* ***zIndex*** (*number*)
* ***style*** (*object*, passed to the wrapping div)


## Examples

```html
<Matrix width={1280} height={720} speed={2} />
```

```html
<Matrix fullscreen={true} color={'#FF0000'}  />
```

## Default Options

* width 640px
* height 480px
* fullscreen false
* colSize 11
* fontSize 13.5
* color '#00cc33'
* frequency 0.005
* speed 1.6

## Contributing

Feel free to open an Issue or send me a direct message.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/Sadkit/react-matrix-effect/tags). 

## Authors

* **Daniele Molinari** - [Sadkit](https://github.com/Sadkit)

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE.md](LICENSE.md) file for details.
