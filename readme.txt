For the skill assessment, we will be testing out your ability to pick up someone else's code and take it to the next level. 
For the hypothetical situation, a FED has been working on a project but got pulled off so we need your help.

Here's what the FED has to say:

This is where we got to in the cut, but we are having problems and haven't been able to fully test. 
Can you help us resolve the following issues as well as help catch if we missed something?
The client is very particular about having fast page speed, good SEO, and wants interesting interactive pieces.
Support wise they also want to have this page look right in browsers that are over 5% of the browser stats for the US over the past couple of months
Below are the items we haven't been able to get to yet.

Font:
  - We set up the Allura and Alex Brush font family stacks in the CSS but we don't have the fonts included

Site Logos:
  - We need to account for retina screens

Icons:
  - We haven't been able to add the icons to the setup yet
  - Hamburger menu, cart, and search icons haven't been added

Navigation:
  - We haven't setup functionality for the menu toggle to open up the bottom footer area in small screens

Slideshow:
  - We need another slide created from the PSD 
  - The styling isn't right yet for slide content as well
  - We also haven't been able to set up the slide functionality

Footer:
  - We got a fair amount of responsive styles done for the site however the footer isn't quite there yet
  - Social media icons need to be setup so some html changes there to put them in is fine.
  - Expander accordion Javascript functionality hasn't been setup or styled
  - Footer bottom area: we unfortunately can't pull the html content out of its location
     - Can we style up the setup so it matches the desktop and mobile styles

Responsive:
  - For some reason the site isn't switching over to "mobile" styles in devices
  - Also when you shrink down the browser some sort of content is causing a horizontal scrollbar in smaller screens
  - In between sizes for tablet portrait feel fairly empty, is there something we can style to make them look better


The client is very active in the project and wants a technical breakdown of what you did and how you resolved the missing items. 
So we need a writing assessment as well as the code above. 
They also want to know how the design UI/UX and FED code practices could be improved down the road, so please include that as well in your writing. 

-------------------------------------------------------------------------------------------------------------------------
Font: 
- added fonts Allura and Alex Brush from Google fonts

Site Logos:
- LOOK INTO RETINA SCREENS

Icons:
- added shopping cart icon in html where it was asked
- added search svg to folder of images
- added search icon in html where it was asked
- added hamburger-menu svg to folder of images
- added alt text to icons to make more accessible and explain what icons would do
- ADD HAMBURGER ICON TO MOBILE VIEW

Navigation:
- look at toggle in mobile PSD

Slideshow:
? ask if they mean if I need to create another PSD for slide design, bc I don't have PSD
? what part do they want to change with the slideshow? New image/baby or whole new slide with new content?
- added gradient background to slide__content
- added 8px of padding to slide__content
- added white border as shown in PSD to slide__bg img
- gave inner outline and figcaption transparency of .8
- added object-fit property to slide img so new images scale to height of original image

Footer:
- fixed footer with .outside class to have bottom footer outside of body as shown in PSD
- included social media icons now
- made social media icons more accessible with clear alternative text about what icons do
- ADD ACCORDIAN

Responsive:
- added meta viewport to have screen width match device width
- LOOK INTO MOBILE SCREEN COMPATIBILITY


Research Links:
https://blog.hubspot.com/website/accessible-icons
https://brand.wwu.edu/accessibility/guide/graphics-used-links-and-buttons-need-accessible-names
https://developers.google.com/web/fundamentals/performance/rendering/
https://github.com/Keyamoon/IcoMoon-Free/tree/master/SVG
