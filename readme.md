# Shaman

Shaman is a fork of [CSSWizardry Grids](https://github.com/csswizardry/csswizardry-grids) and includes the following changes;

- Changed word based class names to numbers (--1-2 rather than --one-half)
- Added default grid class "col" to target all breakpoints
- Minor tweaks and improvements

`npm install shamangrid`

### Settings

Example settings:

```scss
$base-grid-size:                1100px;
$mobile-first:                  true;
$responsive:                    true;
$gutter:                        14px;
$use-silent-classes:            false;
$push:                          true;
$pull:                          false;
$use-markup-fix:                false;
$use-silent-classes:            false;

$breakpoint-has-widths: ('tablet', 'desk')   !default;
$breakpoint-has-push:   ('tablet', 'desk')   !default;
$breakpoint-has-pull:   ('tablet', 'desk')   !default;

$tablet-breakpoint:             48em;
$desk-breakpoint:               68.75em;

$grid-breakpoints: (
    'tablet' '(min-width: $tablet-breakpoint)',
    'desk' '(min-width: $desk-breakpoint)'
) !default;
```
