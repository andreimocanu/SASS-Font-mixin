# SASS-Font-mixin
An easy to use mixin for generating font css.

All you have to do is include the following:

@include font(12rem, 1.2, 700, #000);

It will generate:

font-size: 12rem;
line-height: 1.2;
font-weight: 700;
color: #000;


@mixin font($size, $line: null, $weight: null, $color: null) {
    font-size: $size;
    line-height: $line;
    font-weight: $weight;
    color: $color;
}
