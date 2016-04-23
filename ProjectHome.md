This javascript easily allows you to have "floating" table headers on a table that will stay in your browser window if the user scrolls the page.  The "floating" effect will only happen if the table is in the view and the header row is no longer on the page.

This script has been tested and works successfully in IE 6.0, IE 7.0, and FireFox 3.0.7.  It hasn't been tested in Opera, Chrome, or any other browsers.  Please let me know if you have success (or not) with any of these.

See [Usage](http://code.google.com/p/js-floating-table-headers/wiki/Usage) for instructions on how to use this script.

I've found that if you use `<table border=...>` it doesn't work correctly.  I'm not sure why, but putting a 'border' attribute on a table tag somehow isn't managed by css, so I cannot pull the proper css attributes to copy them to the floating header.  The fix for this is to use `<table style='border: ...'>` so it can be properly copied to the floating table header.