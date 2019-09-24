Instructions
In this assignment, you're given the HTML and CSS for a standard static website with a variety of elements (text and images) nested within sections and wrappers. The layout is primarily fixed--that is, it uses pixels instead of percentages, ems, rems, or vh/vw for sizing. 

Your task is to adjust the CSS of this project using responsive measurement units, scalable image properties, and media queries so that when you narrow the browser to tablet- and mobile-sized viewports, the width, size, and other styling elements adjust to be completely viewable and readable in all viewport sizes. Use Chrome Devtools to test your design as you go. If necessary, you can also use it to locate and create new breakpoint measurements to add to your media queries.

Here are the steps:

Download the starter code attached below and open it in your text editor.
Download the Lab 5 images attached below and take a look at them to get an idea of what you're going for in desktop and mobile views.
Add your viewport meta to the <head> of your index.html: <meta name="viewport" content="width=device-width, initial-scale=1.0">
Add to CSS: * { box-sizing: border-box; }
Add the appropriate set of desktop-first media queries/breakpoints to your CSS, ready to populate with appropriate styles for each viewport size (these are pasted below for your convenience).
Here are the specific requirements:
The "some kafka" content area should move to appear beneath the large picture in mobile view.
The navigation menu items should move closer together in tablet view, then collapse into a Slicknav menu (as described in the textbook and Responsive Web Development slides) in mobile view.
All images, logos, text areas/columns, and text sizes should scale down to fit into a mobile view. This usually means a slightly larger default font in relation to slightly smaller header fonts and fluid column/container sizes.
Add appropriate fluid margins, padding, and other styling around the site for all views.
Add other styling and content as necessary to customize your site (this part is secondary; focus on creating functional media queries, Slicknav menu, and responsive content).
Desktop-first media queries/breakpoints

In this project, desktop is the default, so any styles that won't change or should remain the same (such as colors, font styles, etc.) go first in your CSS and do not need to be wrapped in a media query.
 
/* media query for tablet portrait layout (768px to 959px) */
@media only screen and (max-width: 959px) {
    ...all styles specific to tablet portrait view go here }
 
/* media query for mobile landscape layout (480px to 767px) */
@media only screen and (max-width: 767px) {
    ...all styles specific to mobile landscape view go here }
 
/* media query for mobile portrait layout (479px or less) */
@media only screen and (max-width: 479px) {
    ...all styles specific to mobile portrait view go here }
