# Responsive Web Design 

## Objectives 

##Introduction:

In this project, I exploring some basic techniques for creating responsive web design using HTML and CSS. Responsive web design allows a website to adapt to the dimensions of the device it is being viewed on, whether it be a smartphone, tablet, or computer. By using breakpoints and media queries, I can create a seamless user experience across all devices.

    1. Change the color:

To change the background color of the body element based on the width of the viewport, I will first need to create an HTML file and a CSS file. In the HTML file, I can include the following element to define the body:

In the CSS file, I can then use media queries to specify different styles for different viewport widths. For example, to make the background color of the body red when the viewport width is smaller than 480px, green when the viewport width is bigger than or equal to 480px and smaller than 1024px, and blue when the viewport is bigger than or equal to 1024px.

480 and 1024 are also called breakpoints, as they are typically used as thresholds between different device types. For example, a width of 480px or less might be associated with a smartphone, while a width of 1024px or greater might be associated with a computer.

    2. Display/hide elements:

To display or hide elements based on the width of the viewport, I can use the same technique of media queries in the CSS file. For example, to display only one div at a time according to the width of the viewport.

    3. Adapt the size of the text according to the device:

To change the font size of the text in each div according to the device type, I can use media queries in our CSS file to specify different styles for different viewport widths. For example, to make the font size larger for larger devices and smaller for smaller devices.

Finally, I will rearrange the layout of the div elements based on the viewport width. For the first media query, I will set the div elements to be stacked on top of one another. For the second media query, I will set the first div to take up 2/3 of the width, the second div to take up 1/3 of the width, and the third div to take up the full width. For the third media query, I will set the div elements to be next to one another.

In summary, I have demonstrated how to use media queries and CSS to change the color, display, and size of elements in an HTML file based on the width of the viewport, as well as how to rearrange the layout of the elements. By using media queries and CSS, we can create responsive designs that adapt to different device types and viewport sizes.

Here is an example of the HTML and CSS code to implement the points outlined above:

##HTML: 

##CSS:

To rearrange the layout of the div elements based on the viewport width, I use additional styles in my CSS file. For example, to stack the div elements on top of one another for small viewports, and set the first div to take up 2/3 of the width and the second div to take up 1/3 of the width for medium viewports, and set the div elements to be next to one another for large viewports, we can use the following styles:


With these styles in place, the layout of the div elements will adapt to the width of the viewport, resulting in a responsive design that adjusts to different device types and viewport sizes.
