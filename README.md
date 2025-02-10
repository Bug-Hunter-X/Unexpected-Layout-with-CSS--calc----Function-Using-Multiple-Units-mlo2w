# Unexpected Layout with CSS `calc()` Function Using Multiple Units

This repository demonstrates an uncommon bug related to the CSS `calc()` function. The bug occurs when using multiple units within the `calc()` function, leading to unexpected layout results in some browsers.

## Bug Description
The provided CSS code uses the `calc()` function to calculate the width of a div element. The calculation involves subtracting pixels from a percentage value. While this works correctly in most browsers, some browsers might produce unexpected results due to inconsistencies in interpreting and handling the `calc()` function with mixed units.

## Bug Reproduction
1. Clone this repository.
2. Open `bug.html` in different browsers.
3. Observe the layout differences.

## Solution
The issue can be resolved by using consistent units within the `calc()` function or using alternative methods for calculating the width. The solution uses percentages only, providing a consistent layout across different browsers.  A media query could also be implemented to provide a more responsive design.