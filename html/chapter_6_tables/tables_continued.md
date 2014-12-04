# TABLES CONTINUED:

Long tables have 3 extra traits:

Headings of the table should sit inside the <thread> element
The body element should sit inside the <tbody> tag
And the footer belongs in the <tfooter>

One of the reasons to have a seperate <thead> and <tfooter> tag is so that if you have a table that is longer than the screen itself, the the header and the footer remain visible whilst the table contents scroll up or down.

To summerise:

The <table> element is used to add tables to web pages
They are drawn out row by row <tr>
Inside each row there are a number of cells represented by the <td> or the <th> if it is a header
You can make cells span more than one row or column using the rolspan or colspan attributes
Long tables will need a <thead>, <tbody>, and <tfoot>