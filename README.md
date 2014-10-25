fadeScroll
==========

An angular directive that causes an element to fade away as you scroll through a page.

###Documentation

There are two variable set to the directive scope.
* fade - The number set here represents how fast the element will fade when scrolling; the default is 1; to see how it actually works look at the javascript code.
* start - This number decides when the fading will kick in; the default is 0.

###Example

`<div fade-scroll fade="2" start="500">`

The element will begin to fade out at 500 pixels from the top, and the rate will be twice that of normal.

`<div fade-scroll>`

The element will beging to fade out immediately at the default rate.
