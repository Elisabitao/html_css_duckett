# IMAGES CONTINUED

* Vector images:
When an image is an line drawing - such as a logo or illustration or diagram- designers will often create it in VECTOR format, aka, lines which connect on a grid in order to create a final design. The shapes they form can be edited and filled in with colour etc. The advantage here is that you can increase the lines of the image without affecting the quality of it.
    * The current method of using a vector image for display on a website involves saving a bitmap version and using that.


* Animated Gifs:
These are essentially very simple animations, which contain only a few frames that may or may not be on repeat.


* Transparency
This will involve 2 formats for the designer, either __PNG__ or __GIF__:
    * If the transparent part of the image has _straight edges and is 100% transparent (i.e semi-opaque)_, the image can be saved as a __GIf__.
    * if the transparent part of the image has _diagonal_ or _rounded edges_, or if you want a _semi-opaque transparency_, or even a _drop shadow_; then it will need to be saved as a __PGN__.

## FIGURE CAPTION TAG

HTML5 has a new tag that includes the caption option for the image in question. You can have more than one image inside the ```<figure></figure>``` tags provided you want all the captions to be the same:

```html
<html>
  <head>
    <title>Image captions</title>
  </head>
  <body>
    <h1>Captions</h1>
    <figure>
      <img src="Desktop/the-struggle.jpg" alt="baby elephant trying to go uphill">
      <br />
      <figcaption>Here is my life learning code....</figcaption>
    </figure>
  </body>
</html>
```
