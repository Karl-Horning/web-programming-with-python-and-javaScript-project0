# Web Programming with Python and JavaScript: Project 0

project0 contains the site 'LDN' which is made up of four pages and gives users recommendations of the best places to visit in London.

The project requirements and the fulfilled requirements (all) have been included below so as to make them easy to compare.

The Completed Requirements also include descriptions of where to find the fulfilled requirements.

## Project Requirements

* Your website must contain at least four different .html pages, and it should be possible to get from any page on your website to any other page by following one or more hyperlinks.
* Your website must include at least one list (ordered or unordered), at least one table, and at least one image.
* Your website must have at least one stylesheet file.
* Your stylesheet(s) must use at least five different CSS properties, and at least five different types of CSS selectors. You must use the #id selector at least once, and the .class selector at least once.
* Your stylesheet(s) must include at least one mobile-responsive @media query, such that something about the styling changes for smaller screens.
* You must use Bootstrap 4 on your website, taking advantage of at least one Bootstrap component, and using at least two Bootstrap columns for layout purposes using Bootstrap’s grid model.
* Your stylesheets must use at least one SCSS variable, at least one example of SCSS nesting, and at least one use of SCSS inheritance.
* In README.md, include a short writeup describing your project, what’s contained in each file, and (optionally) any other additional information the staff should know about your project.


## Completed Requirements

- [x] four different .html pages: index.html, about.html, links.html, and contact.html
- [x] possible to get from any page to any other page by following the four hyperlinks included in the navbar
- [x] two unordered lists are included on the index.html page (under 08. British Museum and 10. Camden Market)
- [x] two tables are included in the links.html file
- [x] background images are included on each page; a standard image is included in the about.html page
- [x] five stylesheet files: fonts.css, forms.css, images.css, styles.css, and tables.css
- [x] multiple CSS properties and CSS selectors (including the #id selector and the .class selector) are used across the five files
- [x] one media query is included in the styles.css file (line 121) that styles the navbar for mobiles; a number of media queries are included in the images.css file (starting at line 81) that change the page images based on the screen size
- [x] Bootstrap 4 is included on each page
- [x] Bootstrap components are included in each page: containers are included across the site, the about page uses Bootstrap responsive images, the links page uses Bootsrap responsive tables, and the contact page uses Bootstrap responsive forms
- [x] Bootstrap single columns are used throughout the site; multiple columns are used for the Tube lines within each entry on the index.html page; double columns are used on the contact.html page for the 'Name' and 'Email' fields.
- [x] seven Sass files are included: font-faces.scss, global.scss, fonts.css, forms.css, images.css, styles.css, and tables.css - global.scss and fonts.css both include SCSS declarations and the all of the files use SCSS variables
- [x] tables.scss includes two examples of SCSS nesting
- [x] fonts.scss and images.scss both include examples of SCSS inheritance
- [x] README.md included with a short writeup describing the project and what’s contained in each file


## References

Perfect Full Page Background Image:
https://css-tricks.com/perfect-full-page-background-image/

Right Aligned Nav:
https://www.w3schools.com/bootstrap4/bootstrap_navs.asp

Are Safari & Mobile Safari rendering rounded borders with radius and padding incorrectly?:
https://stackoverflow.com/questions/14444806/are-safari-mobile-safari-rendering-rounded-borders-with-radius-and-padding-inc