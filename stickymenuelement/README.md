# Stickable

Simple jQuery plugin to stick a div at the top of the viewport when it goes out while scrolling.

## Usage

Link the CSS file, or just copy the class definition `.istick` in your CSS:

```css
.istick {
   margin-top: 0 !important;
   position: fixed;
   top: 0;
   z-index: 10000;
}
```
Insert the js file after jQuery:

```html
<script type="text/javascript" src="/path/to/stickable.js"></script>
```

Just apply the plugin to the div to be sticked:

```javacript
jQuery( document ).ready( function( $ ) {
	
	$( 'myDivToStick' ).stickable();

});
```
Very simple.

[jsfiddle](https://jsfiddle.net/xavier_bs/78w7srd9/16/)

***

No licence.

_Xavier Birnie-Scott_
[murviel-info.com](http://murviel-info.com)