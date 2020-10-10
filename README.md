# Portfolio

This week's project was to start working on our portfolio. The main focus for this week was to get the technical part of the site in to place with html and css, but also to get started accessibility and build websites for everyone.

# The Work Process

- I started with creating the html-skeleton of site. I tried to use as semantic tags as possible. When looking back on the process now I realise I could have put in more time here and added for example article elements on blog-posts and try to rename some of the other non-semantic div-tags.
- I chose to work with desktop first in mind since I thought about what device the user (hopefully recruiters :smirk: ) would use in an office environment. However from a work flow perspective I would have chosen mobile first since I had to do it again, since the layout seems easier to scale up than down. Especially the header part where the profile picture was difficult to get in place.
- Since I'm a part of the career program I chose to work from the provided design template in the brief. This was both fun an challenging! I would like to continue on the styling and give the site a more personal touch for future updates.


# Accesibility and cross-browser testing:
- cross-browser testing in Google chrome, Edge and Firefox. The website looks ok in all three browsers. Had a a bug with the margin-top for mobile in safari for iphone, but i think I solved it by adding position to parent and child element instead. 
- screenreader tested in Chrome. Have one minor issue with "My thoughts" heading that is not read since it's on display none for mobile.
- tab-navigation is tested in Chrome, Edge and Firefox. 
- aria-hidden="true" is applied to element that creates more confusion than clarity when screen reader reads them.
- I have added text-decoration on hover for links to make it more clear that these elements are clickable.
- when using the lighthouse report the website got 92% in accessibility for desktop and mobile.

To work on:
- The heading structure. When doing the HTML-validation test I noticed that my headingstructure isn' in order. I will have to work on this on future updates for the portfolio. I would like to have some feedback and help regarding this for my code review.

# View it live:
https://laughing-mcnulty-5ff157.netlify.app/
