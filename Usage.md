# Introduction #

This script makes it REALLY easy to keep table header rows on the screen while the user scrolls up and down the page

# Details #

3 Steps:
  1. Download table\_floating\_header.js and put it in your HTML directory.  Make sure you give the web server user access to view the js
  1. Add this line anywhere in your HTML:  

&lt;script type="text/javascript" src="table\_floating\_header.js"&gt;



&lt;/script&gt;

**1. Put**`<thead></thead>`**around the rows you want to keep on the page**

That's it!

Example HTML page:
```
<html>
<head>
<script type="text/javascript" src="/js/table_floating_header.js"></script>
</head>
<body>
<table>
<thead>
<tr><th>Customer Contact Information</th></tr>
<tr><th>Name</th><th>Address</th><th>Daytime Phone</th><th>Evening Phone</th><th>Cell Phone</th><th>Work Phone</th></tr>
</thead>
<tr><td>customer 1.....</td></tr>
.
.
lots more rows here
.
.
.
</table>
</body>
</html>
```