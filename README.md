# Horiseon Website

## Provide a professional looking website for the company Horiseon.

### Criteria:

GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

#### Overall changes:

One of the first steps that I took to clean up the html and css code was to section off the code with comments to know what each part of the code focused on. I did this for both the html and css files.

#### CSS changes:

I focused on the CSS syntax. I noticed there was too much repetitive code that could be condensed into smaller groups, but still keep the features. I started with making a new selector (.content-section) in CSS and class in HTML in order to combine the syntax that focused on the text and boxes for the Search Engine Optimization, Online Reputation Management and Social Media Marketing sections. I went ahead and applied the same concept for the Content’s img and h2 elements. Next came the Benefits sections. I went ahead and combined the benefit sections by creating a class of ‘benefit-section’. This allowed me to combine the Lead Generation, Brand Awareness and Cost Management sections into one CSS syntax. I applied this concept to the Benefits img and h3 elements. This change resulted in going from nine CSS syntax for the Content and Benefits sections to 3 for each. After combining the css syntax, I went ahead and changed the background colors of the Content and Benefit sections to match the background color of the header, moved the .float-left and .float-right to the Content section in the CSS file, changed the value to ‘52px’ for the property ‘margin-bottom’ in the .benefit-section selector to line up with the Content.

#### Html change:

Added Hiroseon in the <title> element in the head, added an ID to the search-engine-optimization div element in order for the link in the header to work, changed specific classes to “content-section” for the Search Engine Optimization, Online Reputation and Social Media Marketing divs in order to connect with the new CSS syntax. The same concept was applied to the Benefits’ section. A new class was created, benefits-section, in order to connect with the changes in the CSS stylesheet. ALT was added to all the images in order to be read by screen readers and prevent legal actions by their customers. The final change was to correct the Cost Management’s img element as it did not need a closing tag. Moved the img url to html and added alt attribute.
