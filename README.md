# Flexbox Grid Sass

This library was maintained by [Huge Inc](https://www.hugeinc.com/) but was abandoned sometime ago. I will be updating this repo with the former PRs and possibly tweak some configs. PRs are welcome.
This work is an adaptation from the original [Flexbox Grid](http://flexboxgrid.com/) created by @kristoferjoseph.
Grid based on the `flex` display property. [Check the documentation](http://hugeinc.github.io/flexboxgrid-sass)

## Use

`Copy the flexboxgrid.scss into the sass directory of your project`

`@import 'flexboxgrid'` from your main sass file.

## Customize

At the top of flexboxgrid.scss are all the variables you can customize:

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

[x] Remove Bower/Gulp

[ ] Move \$variables into their own file
