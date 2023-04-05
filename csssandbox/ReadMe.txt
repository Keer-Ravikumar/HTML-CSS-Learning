• To find color combination for Websites - https://colorhunt.co/palettes
• To find HEX value of the color - https://www.color-hex.com
---

• To find free source images:
https://www.pexels.com/ 
https://unsplash.com/
---

• To Find Theme Ideas for website
https://themes.getbootstrap.com/
https://nicepage.com/website-templates
---

• Forms
Form >> Form Wrap( The entire form ) >> Form Group( The Label and the Input Box )
>> form button ( Usually the sign up and login ) 
---

• You can add or more conditions in a media query: 
@media( min-width: 501px ) and ( max-width: 798px )
---

• You can have a seperate stylesheet for a specific dimension and link the css sheet 
to the html file:
<link rel="stylesheet" media="screen and (max-width: 798px)" href="style.css">
---

• EM and REM:
EM is the size multiplier of parent unit and REM is the size multipler of root unit.
Prefer to use REM than EM because this could be confusing.
REM is more responsive and adaptive.
---

• Grid:
When a div block's display is changed to grid, the entire div block becomes a grid container.

To define Grid Template rows/columns, you can either use:
    grid-template-rows: repeat(3, 1fr)
                ( or )
    grid-template-rows: 1fr 1fr 1fr
Both serve the same purpose. (1fr refers to 1 fraction of the space)

We can also define the row gap and the column gap using row-gap and column-gap properties.

We can also define the start line and end line of a specific grid as well by using:
    grid-column-start: 1;
    grid-column-end: 4;
This code merges the 3 grids into 1.

Instead of the above code this also can be used:
    grid-column: 1 / span 3
This also merges 3 grids into 1.

You can also use Justify property on the grid container to justify contents to the start, centre, or end.
    justify-items: center
Justify-Items work on grid containers and Justify-Self works on grid item.
    justify-self: center

Horizontally center - Justify
Vertically center - Align

Align-Items work on grid container and Align-Self works on grid item.
    align-items: center
    align-grid: center

You can combine both Align and Justify properties and use Place property
    place-items: center
    place-self: center

A container can also be an inline-grid.
This container then displays the properties of both an inline element and a grid element.
---

• Flex:
It is mostly similar to few properties of grid.

Here, we can set the flex-direction row, column, row-reverse, column-reverse

Justify Contents and Align Contents are also used here: flex-start, flex-end, center, etc.,

We have a property called flex-wrap which makes the items responsive with the screen size.
    flex-wrap: wrap
We also have wrap-reverse which reverses the flex-items order.
    flex-wrap: wrap-reverse

We have a property for flex-item called flex-order according to which the items are arranged.
It takes numeric values as parameters 
    order: 3

We also have flex-grow and flex-shrink.
It grows or shrinks according to the screen size.
    flex-grow: 2
    flex-shrink: 3

