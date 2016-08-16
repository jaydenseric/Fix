# ![Fix CSS](http://jaydenseric.com/shared/fix-logo.svg)

![Version](https://img.shields.io/badge/version-1.0.0-brightgreen.svg?style=flat-square)
![Github issues](https://img.shields.io/github/issues/jaydenseric/Fix.svg?style=flat-square)
![Github stars](https://img.shields.io/github/stars/jaydenseric/Fix.svg?style=flat-square)

Styles to fix unruly user agent default CSS. Part normalization, part reset.

Check out the [blog post](http://jaydenseric.com/blog/forget-normalize-or-resets-lay-your-own-css-foundation) that spawned this project.

- Offending rules are surgically targeted. For example, the `padding-left` of `ul` is reset using `padding-left: 0` and not the typical `padding: 0`.
- [MIT license](https://en.wikipedia.org/wiki/MIT_License).

## Usage

You *could* include the whole thing in your project, but these days global CSS is an anti-pattern. Just use the relevent bits when styling component elements.
