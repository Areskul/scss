# Scss

## What it is ?

It is nothing more than a set of css variables accessible in :root pseudo-class.
Please read that sentence again.
I use it with Vue.js mixins for fast (light/dark) theming.

## What for ?

There is many CSS frameworks like Bootsrap and Bulma that focuses on grids and spacing.

This one just focuses on colors and shades.

Greatly inspired by Vuetify color sheme and shades.

It just aims to fasten Colors and Shades usage in CSS by creating sets of variables.

### Usage

For Vue.js usage, please consider using/forking the mixins that goes with.

Firts, clone this repo in your project.

For example we've cloned it into the ./core folder.

Then create a scss/variable.scss file.

## Colors

Basic lightweight theme--light and theme--dark
Define your set of colors. It will create a panel of variables

such as:

```scss
--primary-lighten, --primary-lighten2
```

```scss
\$colors: ("primary": #b81b5c, "secondary": #f71aec, "success": #38fa11);
@import "../core/scss/colors/light.scss";

\$colors: ("primary": #5e6fce, "secondary": #474747, "success": #1b6e0a);
@import "../core/scss/colors/dark.scss";
```

## Animations

Set of minimal must-have animations

```scss
@import "../core/scss/animations/transitions.scss";
```

## Elevation / Shadow

Panel of box-shadows

```scss
@import "../core/scss/animations/transitions.scss";
```

## Breakpoints

Just put your breakpoint values into the :root pseudo classe for accessibility in js mixins
