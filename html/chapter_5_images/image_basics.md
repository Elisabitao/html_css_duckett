# IMAGE BASICS

Images are crucial to websites. Stock images can easily be used/ taken from google in order to add character to a page.

### Images should:
  Be relevant
  Convey information
  Convey the right mood
  Be instantly recognisable
  Fit the colour palette

Images use the ```<img src="" alt="">``` tag. The two attributes are the SOURCE and the TEXT DESCRIPTION (which is often referred to as 'alt text') of the image at hand. You can also use a ```<title="">``` in the 'img' tag, many people use them as a tooltip when the users hover over the picture.

The ```<width="">``` and ```<height="">``` are also common attributes to find in an image, and refer to the pixel number. However!!! this is something that should really be CSS territory and is best practice that way. Here we shall use it as an example but thats it:

```html
<html>
  <head>
    <title>Image example</title>
    <body>
      <h1>IMAGES!</h1>
      <p>here you go: <img src="http://img1.wikia.nocookie.net/__cb20130915151449/p__/protagonist/images/5/53/Grumpy-Disney.jpg" alt="Grumpy Dwarf" width="500" height="700" title="The only dwarf with any sense"></p>
    </body>
  </head>
</html>
```
<br />
Live demo:

<html>
  <head>
    <title>Image example</title>
    <body>
      <h1>IMAGES!</h1>
      <p>here you go: <img src="http://img1.wikia.nocookie.net/__cb20130915151449/p__/protagonist/images/5/53/Grumpy-Disney.jpg" alt="Grumpy Dwarf" width="500" height="700" title="The only dwarf with any sense"></p>
    </body>
  </head>
</html>

Where an image is placed is also important and needs to be seriously considered as placement can have serious effects on display. Three examples are before a paragraph, at the start of one, or even within the middle. Not to mention alignment, be it left or right, or having the first line arranged either on top/ middle/ bottom of the image in question:

__*REFERENCE TEST 3 IN IMAGES FOLDER FOR EXAMPLES*__

