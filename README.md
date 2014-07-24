HTML5 full height, two-column, responsive layout
=================================

A 100% height, responsive, two-column layout with header and footer.

![Layout](http://i.imgur.com/jhtY6Dz.png)

Uses `display: table` (eek!), and bootstrap's grid for easy column wrapping (although it doesn't need it).

Results vary A LOT depending on the browser. Firefox seems to have the best rendering at the moment.
It displays well in Chrome, Firefox, and IE8+ thanks to the html5shiv and Respond.js.

I've tried some other approach using `display: table-caption` will only work for either the header or the footer, but not both at the same time.

My 2 cents: CSS should have element anchoring and docking like the one that is available in Visual Studio. But let's see where flexbox gets us in the future :)
