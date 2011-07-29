jQuery ticker plugin
--------------------

License
=======
Copyright (c) 2011 Radek Pleskac www.radekpleskac.com
Dual licensed under the MIT and GPL licenses.
http://www.opensource.org/licenses/mit-license.php
http://www.gnu.org/licenses/gpl.html

Copyright Radek Pleskac
 
Requirements
============
jQuery v1.3.2+ 

Description
=========== 
jQuery plugin to turn an unordered list <ul> into a simple ticker, displaying one list item at a time

Examples
========

HTML structure

<ul id="ticker1">
  <li>1 - First item - Lorem Ipsum is simply dummy text of the printing and typesetting</li>
  <li>2 - Second item - Lorem Ipsum is simply dummy text of the printing and typesetting</li>
  <li><a href="">3 - Third item - Lorem Ipsum is simply dummy text of the printing and typesetting</a></li>
  <li><a href="">4 - Fourth item - Lorem Ipsum is simply dummy text of the printing and typesetting</a></li>
</ul>

- Effect fadeIn (default)

$("#ticker1").ticker();

- Effect slideUp

$("#ticker2").ticker({ effect: "slideUp"});

- Effect slideDown

$("#ticker3").ticker({ effect: "slideDown"});

- Options

$.fn.ticker.defaults =  {
	controls: false, //show controls, to be implemented
	interval: 3000, //interval to show next item
	effect: "fadeIn", // available effects: fadeIn, slideUp, slideDown
	duration: 400 //duration of the change to the next item
};
				
