# Responsive Web Design 

## Objectives 

###Introduction:

In this project, I exploring some basic techniques for creating responsive web design using HTML and CSS. Responsive web design allows a website to adapt to the dimensions of the device it is being viewed on, whether it be a smartphone, tablet, or computer. By using breakpoints and media queries, I can create a seamless user experience across all devices.

    1. Change the color:

To change the background color of the body element based on the width of the viewport, I will first need to create an HTML file and a CSS file. In the HTML file, I can include the following element to define the body:

In the CSS file, I can then use media queries to specify different styles for different viewport widths. For example, to make the background color of the body red when the viewport width is smaller than 480px, green when the viewport width is bigger than or equal to 480px and smaller than 1024px, and blue when the viewport is bigger than or equal to 1024px, we can use the following styles:



480 and 1024 are also called breakpoints, as they are typically used as thresholds between different device types. For example, a width of 480px or less might be associated with a smartphone, while a width of 1024px or greater might be associated with a computer.

    2. Display/hide elements:

To display or hide elements based on the width of the viewport, I can use the same technique of media queries in the CSS file. For example, to display only one div at a time according to the width of the viewport, I can use the following styles:



    3. Adapt the size of the text according to the device:

To change the font size of the text in each div according to the device type, I can use media queries in our CSS file to specify different styles for different viewport widths. For example, to make the font size larger for larger devices and smaller for smaller devices, I can use the following styles:



