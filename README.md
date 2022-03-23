# Sign Up Form

Mock Sign Up form for a fake service. An assignment given by The Odin Project to be modeled after [this design](https://cdn.statically.io/gh/TheOdinProject/curriculum/5f37d43908ef92499e95a9b90fc3cc291a95014c/html_css/project-sign-up-form/sign-up-form.png)

The purpose of the assignment was to create a basic html form and practice styling forms with css. 

I chose to use a different image and text content to work with a different color scheme and add some humor to the project.

The one feature I did not implement was the password error class. It does not seem possible for client side validation of password matching using pure html and css. I think Odin meant for us to keep this in mind for later (assuming we'll revisit this project). I'll be on the look out for how this feature is to be implemented.

## Limitations

Based on my current knowledge of css this syling is far from ideal. Learning flexbox I was able to keep the form usable at various resolutions and keep the design from totally breaking, but some obvious improvements lay in:

The headers in the main body: I had to resort to resizing the text based on the size of the viewport, but at small resolutions it would not be readable for some, and zooming in does not increase the font size. I'm interested to learn how i can handle this text in a more accessible way, while still pushing it out of the way of the form fieldset. 

The left image panel: is one large div with an inline image tag. I was not able to get the image to properly fill out the div how I would have liked. When the viewport's length is much greater than its height, the logo div begins to flow off the image and into the form panel. Perhaps learning Grid next week will provide some insight for a better design.

Another issue with the left panel is when the viewport is very narrow, the logo text flows into the form fields. My quick fix was to just hide the overflow, but the ideal for me in a later version would be to use media queries to completely move the left panel to a small section above or below the form, in the case of narrow resolutions.


I was happy to get the form inputs to switch to a column view when the viewport is narrow! At no point (in the resolutions i can test) is a horizontal scrollbar necessary which I think is important.