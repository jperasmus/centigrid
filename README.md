centigrid
=========

This is a very basic responsive grid using percentages instead of default columns. The grid is more for personal use, but if it could help someone, go ahead and use it. It is based on Zurb's Foundation 5 grid, so most credit should go to them.

Horizontal rows can be created using the class "row".

Vertical columns can be created using the class "col" together with the different breakpoint class. This is better explained with an illustration:
To create a column of 70% on a small screen and 50% on a medium screen, you will use &lt;div class="s-70 m-50 col"&gt;&lt;/div&gt;

Since it is based on the Foundation grid, it is mobile first, so for our previous example large and bigger screens will inherit the 50% grid from the medium class specified.

In the scss file you can specify a number of variables for the row width, the default gutter between columns and the breakpoints for the different sizes.