# ![Fix](fix-logo.svg?raw=true)

A quick reference for patching up unruly browser CSS defaults. Part normalization, part reset.

Offending rules are surgically targeted. For example, the `padding-left` of `ul` is reset using `padding-left: 0` and not the typical `padding: 0`.

You *could* include the whole thing in your project, but these days global CSS is a no no. Only use the relevent bits when working on components.

Check out the [blog post](http://jaydenseric.com/blog/forget-normalize-or-resets-lay-your-own-css-foundation) that spawned this project.

## Todo

- Document rules.
- Add more rules, particularly for inputs.

## Licence

[MIT license](https://en.wikipedia.org/wiki/MIT_License).
