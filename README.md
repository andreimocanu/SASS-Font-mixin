# SASS Font mixin
An easy to use mixin for generating font css.

All you have to do is include the following:

<h3>Usage</h3>

<pre>
.selector {
    @include font(12rem, 1.2, 700, #000);
}
</pre>

<h3>Result</h3>

<pre>
.selector {
    font-size: 12rem;
    line-height: 1.2;
    font-weight: 700;
    color: #000;
}
</pre>
