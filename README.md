# sass-breakpoints

[![npm version](https://badge.fury.io/js/sass-breakpoints.svg)](https://badge.fury.io/js/sass-breakpoints)

Breakpoint viewport sizes and media queries from Bootstrap.

## Usage

```bash
npm install sass-breakpoints
```

```sass
$grid-breakpoints: (
  xs: 0,
  sm: 576px,
  md: 768px,
  lg: 992px,
  xl: 1200px
) !default;

@import 'node_modules/sass-breakpoints/mixins/breakpoints';

@include media-breakpoint-up(sm) {
  // ...
}
```