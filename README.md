# Changing Dimensions
This example demonstrates how the .height() and .width() methods can be used to retrieve and update box dimensions. These methods allow you to discover or update the width and height of all boxes on the page. If you set the width or height of the box in CSS, it does not include any padding, border, or margin - they are added to the dimensions. The page displays the height of the container. It then changes with width of the list items using percentages and pixels.

## Components that make the app run
* A variable called listHeight is created to store the height of the page container. It is obtained using the .height() method.
* The height of the page is written at the end of the list using the .append() method and may vary between browsers.
