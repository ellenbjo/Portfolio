# Portfolio

This week's project was to start working on our portfolio. The main focus for this week was to get the technical part of the site in to place with html and css, but also to get started accessibility and build websites for everyone.

Accesibility and cross-browser testing:
- cross-browser testing in Google chrome, Edge and Firefox. The website looks ok in all three browsers. Had a a bug with the margin-top for mobile in safari for iphone, but i think I solved it by adding position to parent and child element instead. 
- screenreader tested in Chrome. Have one minor issue with "My thoughts" heading that is not read since it's on display none for mobile.
- tab-navigation is tested in Chrome, Edge and Firefox. 
- aria-hidden="true" is applied to element that creates more confusion than clarity when screen reader reads them.
- I have added text-decoration on hover for links to make it more clear that these elements are clickable.
- when using the lighthouse report the website got 92% in accessibility for desktop.

To work on:
- The heading structure. When doing the HTML-validation test I noticed that my headingstructure isn't in order.
