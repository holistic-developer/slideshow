# slideshow
An HTML template to build slideshows without using javascript (necessarily).

The slideshow's content should be writeable in pure HTML without adding CSS rules or classes (necessarily).  

Semantic tags not only make the content in raw form well structured but also allow the presentation to be accessible.

# Why?
Building slideshows in this way makes it simple to pass them to everybody without the need for any special software to view it.

It allows one to use all kinds of features from web browsers in their slideshows

- Structured text
- Images
- Videos
- Responsive representations
- Interactivity (if some javascript is inlined)

# How?
The whole presentation is one large scrollable content.

Scroll snapping is used to handle pagination and align the slides centered on the screen.

CSS rules are using semantic tags as selectors, thus eliminating the need for classes.