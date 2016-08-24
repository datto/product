# CSS Utility Classes

A *utility class* applies a single rule or a very simple, universal pattern. Think `.float-right`, `.text-center`, and `.bg-primary` for single rules; `.list-unstyled`, `.clearfix`, and `.sr-only` for patterns.

Utility classes help minimize the need for writing application specific layout styling. For example, if you want to provide some vertical space between two elements, instead of writing a new CSS class, slap on `.u-margin-x-lg` and be done.

If you use Bootstrap, you are already familiar with this concept. Bootstrap calls them "[helpers](http://getbootstrap.com/css/#helper-classes)".

## Using

Available via Bower or NPM:
```
bower install --save http://github-server.datto.lan/UI-Components/css-utility-classes
npm install --save http://github-server.datto.lan/UI-Components/css-utility-classes
```

Compiled source files can be found in the `dist/` folder.

## Branding Variables

This project also contains a couple of Datto-branding-specific SASS variable sheets:
* Branding colors: `src/variables/_color-palette.scss`
* Common sizing (fonts, margins, padding): `src/variables/_factor.scss`

*TODO: include LESS variables*

## Documentation

//TODO pretty documentation

Backgrounds:
* To indicate status:
  * .u-bg-green (success)
  * .u-bg-yellow (warning)
  * .u-bg-red (error)
* Helpers:
  * .u-bg-transparent
  * .u-bg-white
* Datto's primary colors:
  * .u-bg-blue
  * .u-bg-teal
  * .u-bg-citrus
  * .u-bg-midnight
  * .u-bg-gray-70, .u-bg-gray-40, .u-bg-gray-30, .u-bg-gray-20, .u-bg-gray-5, .u-bg-gray-2, .u-bg-gray-1

Borders:
* .u-border (all sides)
* .u-border-top, .u-border-right, .u-border-bottom, .u-border-left
* .u-border-none

Display:
* .u-display-block, .u-display-inline-block, .u-display-inline
* .u-width-auto

Margins:
* .u-margin-lg
* .u-margin-x-lg, .u-margin-y-lg
* .u-margin-top-lg, .u-margin-right-lg, .u-margin-bottom-lg, .u-margin-left-lg
* .u-margin-sm
* .u-margin-x-sm, .u-margin-y-sm
* .u-margin-top-sm, .u-margin-right-sm, .u-margin-bottom-sm, .u-margin-left-sm
* .u-margin-collapse
* .u-margin-top-collapse, .u-margin-right-collapse, .u-margin-bottom-collapse, .u-margin-left-collapse

Padding:
* .u-padding-lg
* .u-padding-x-lg, .u-padding-y-lg
* .u-padding-top-lg, .u-padding-right-lg, .u-padding-bottom-lg, .u-padding-left-lg
* .u-padding-sm
* .u-padding-x-sm, .u-padding-y-sm
* .u-padding-top-sm, .u-padding-right-sm, .u-padding-bottom-sm, .u-padding-left-sm
* .u-padding-collapse
* .u-padding-top-collapse, .u-padding-right-collapse, .u-padding-bottom-collapse, .u-padding-left-collapse

Text color:
* To indicate status:
  * .u-text-green (success)
  * .u-text-yellow (warning)
  * .u-text-red (error)
* Helpers
  * .u-text-white
* Datto's primary colors:
  * .u-text-blue
  * .u-text-teal
  * .u-text-citrus
  * .u-text-midnight
  * .u-gray-70, .u-gray-40, .u-gray-30, .u-gray-20, .u-gray-5, .u-gray-2, .u-gray-1

Text:
* .u-text-small
* .u-label
* .u-label-sm

## Changelog

See [Changelog](CHANGELOG.md).

## Contributing

See [Contributing](CONTRIBUTING.md).
