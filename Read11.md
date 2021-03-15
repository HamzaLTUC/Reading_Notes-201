## Images

• we can control size of image us `width` and `height` property.

• we can use `align-left` or `align-right` or `align-center` to control an image position on the page.

• The `background-image`
property allows you to place
an image behind any HTML
element.



### The background-repeat
property can have many  values:

1.`repeat`:\
The background image is
repeated both horizontally and
vertically.

2.`repeat-x` :\
The image is repeated
horizontally only.\
3. `repeat-y` :\
The image is repeated vertically
only.\
4. `no-repeat`:\
The image is only shown once.

`background-position`:
When an image is not being
repeated, we can use the
background-position
property to specify where in the
browser window the background
image should be placed. like left top , left center.

## Search engine optimization (SEO):
  is the practice of trying
to help your site appear nearer
the top of search engine results
when people look for the topics
that your website covers.

we can improve our website's visibility on search engines by :
 ### On-Page :
a. Page Title
The page title appears at the top
of the browser window or on the
tab of a browser. It is specified in
the `<title>` element which lives
inside the `<head>` element.
 
 b. `URL / Web Address`
The name of the file is part of
the URL. Where possible, use
keywords in the file name.

c. `Headings` \
d. `text` , `link text` \
e.`Page description`  
f. `text on image`  .

• Analytics tools such as Google Analytics allow you to
see how many people visit your site, how they find it,
and what they do when they get there.


## Audio and Video 
The `<video>` and `<audio>` elements allow us to embed video and audio into web pages. 

The controls attribute adds video controls, like play, pause, and volume.

It is a good idea to always include width and height attributes. If height and width are not set, the page might flicker while the video loads.

The `<source>` element allows you to specify alternative video files which the browser may choose from. The browser will use the first recognized format.

The text between the `<video>` and `</video>` tags will only be displayed in browsers that do not support the `<video>` element

Example of adding video:

`<video width="320" height="240" controls>`
  `<source src="movie.mp4" type="video/mp4">`
  `<source src="movie.ogg" type="video/ogg">`

`</video>`