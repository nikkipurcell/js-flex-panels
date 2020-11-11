# js-flex-panels
Click a panel to reveal the hidden message and see more of the background image.

## How Its Done
Uses flexbox to position panels in a grid (lots of nested display:flex), css to hide word elements, and JS to find the click method on a panel then toggle the open class on the panel div. This also looks for the transitionend event for flex to toggle the next css transition based on open-active class.

![JS Flex Panels](js-flex-panels.jpg)
