# Flexbox Grid Sass

This library was maintained by [Huge Inc](https://www.hugeinc.com/) but was abandoned sometime ago. I will be updating this repo with the former PRs and possibly tweak some configs. PRs are welcome.
This work is an adaptation from the original [Flexbox Grid](http://flexboxgrid.com/) created by @kristoferjoseph.
Grid based on the `flex` display property. [Check the documentation](http://hugeinc.github.io/flexboxgrid-sass)

## About

By trying the [Flexbox Grid](http://flexboxgrid.com/) we saw the internal need to a SASS version of it. Thanks to the good work of Kristopher Joseph, we forked his project and sassified it.

## Install

### npm

`npm i pak11273/flexboxgrid-sass --save` or
`yarn add pak11273/flexboxgrid-sass`

### bower

`bower install --save flexboxgrid-sass`

## Use

To modify the Flexbox grid, declare the following variables on your layout .scss

#### Set the number of columns you want to use on your layout.

`$flexboxgrid-grid-columns: 12;`

#### Set the gutter between columns.

`$flexboxgrid-gutter-width: 1rem;`

#### Set a margin for the container sides.

`$flexboxgrid-outer-margin: 1rem;`

#### Create or remove breakpoints for your project

You can modify, remove or create breakpoints before generate the final CSS.

```
$flexboxgrid-breakpoints:
  sm 48rem,
  md 64rem,
  lg 80rem,
  xlg 90rem,
  newbreakpoint 120rem;
```

## Milestones

[x] Implement the existing PRs from the HugeInc repo
[ ] Transition Bower/Gulp to Webpack 4
