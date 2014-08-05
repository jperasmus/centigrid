centigrid
=========

Centigrid is a very basic responsive grid using percentage widths instead of default columns like other grids based on the original 980 grid. The grid is more for personal use to solve my frustrations with more complex grid layouts, but if it could help someone, go ahead and use it. Centigrid is based on [Zurb's Foundation 5 grid](http://foundation.zurb.com/docs/components/grid.html), so most credit should go to them.

Even though the grid is based on Foundaiton 5, it has been updated to be compatible with Foundation 4 as well.

Installation:
-------------

Simply add/include the *centigrid.css* or *centigrid.scss* stylesheet to your project/site.

Usage:
------

* Horizontal rows can be created using the class "**row**".
* Vertical columns can be created using the class "**col**" together with the different breakpoint class. 

h5. This is better explained with an illustration:
To create a column of 73% on a small screen and 56% on a medium screen, you will use **&lt;div class="s-73 m-56 col"&gt;&lt;/div&gt;**

Since it is based on the Foundation grid, it is mobile first, so for our previous example large and bigger screens will automatically inherit the 56% grid from the medium class specified.

h3. Other classes include:

* Offset: 	eg. s-offset-35
* Push:		eg. m-push-28
* Pull:		eg. l-pull-3

h3. Special classes:

To cater for thirds and sixths, which would need decimal percentages, special classes have been included as follows:

* Normal column:	eg. **s-1-3rd**, **m-2-3rds**, **s-1-6th**, **l-5-6ths**

Offsets, pushes and pulls can also be done using these special classes, for instance: **m-offset-1-3rd** to offset on medium devices with one third (33.3333%).

h5. Currently, the only special classes included is:
- One third (**-1-3rd**)
- Two thirds (**-2-3rds**)
- One sixth (**-1-6th**)
- Five sixths (**-5-6ths**)

Most other widths can be achieved using normal percentages. If you need any other specific classes, feel free to let me know or extend it yourself.

To *collapse* a given row, a.k.a. remove the gutter padding, you can use the class "**flat**".

Settings:
---------

In the scss file you can specify a number of variables, which include the row width, the default gutter between columns and the breakpoints for the different sizes. You can also decide whether you want to include grid classes for xs (extra small), xl (extra large) and xxl (double extra large). Small, medium and large are included by default.