[![Quantum Shadows Logo](https://dl.dropboxusercontent.com/u/3106750/github/quantum-shadows-logo.png)](https://github.com/nickpfisterer/quantum-shadows/releases/latest)
==============

Use the drop shadows from Google's [Material Design](http://www.google.com/design/spec/) spec in your Sass projects.

[Codepen Demo](http://codepen.io/nkpfstr/pen/gnJhA)

## Installation
* Install via [Bower](http://bower.io) ```bower install quantum-shadows --save```
* [Download](https://github.com/nkpfstr/quantum-shadows) and add to your project manually

## Usage
> NOTE: Quantum Shadows assumes you already have a solution for dealing with prefixes.

Import Quantum Shadows at the top of your Sass files. For example:

```scss
@import "../bower_components/quantum-shadows/quantum-shadows";
```

Right now, it's just a simple mixin away. The mixin takes a value between 1 and 5 for ```$depth```, where 1 is closest to the surface (smaller shadow) and 5 is the farthest (larger shadow). For example, to include a drop shadow with a z-depth of 1:

```scss
.my-stylish-element {
    @include drop-shadow(1);
}
```

That's all there is to it. I am considering adding more functionality to this in the future, but for now I really just wanted an easy way to use the Material Design drop shadows in my Sass projects.

If you find any bugs or have suggestions for a future version, please feel free to [submit an issue](https://github.com/nkpfstr/quantum-shadows/issues).

## Changelog
**v1.0.0** (10-02-2014):
* First release
* Bower support
* Discoverable on [Sache](http://sache.in)
