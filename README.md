HTML5 full height, two-column, responsive layout
=================================

A 100% height, responsive, two-column layout with header and footer.

![Layout](http://i.imgur.com/jhtY6Dz.png)

Uses `display: table` (eek!), and bootstrap's grid for easy column wrapping.

Results vary A LOT depending on the browser. Firefox seems to have the best rendering at the moment.
Needs some tweaking for IE: I can't seem to get it to stretch to full height. Otherwise, it displays well in IE8+ thanks to the html5shiv and Respond.js. Some other approach using `display: table-caption` will only work for either the header or the footer, but not both at the same time.

My 2 cents: CSS should have element anchoring and docking like the one that is available in Visual Studio.
