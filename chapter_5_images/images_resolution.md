# IMAGE RESOLUTION

## RESOLUTION FORMATS AND BITMAP

__Images created for the web should have an image resolution of 72 ppi__

Computer screens are becoming more and more 'high def' which means the number of pixels per square inch - aka 'the resolution', matters a great deal. It is important to note that the higher the resolution the longer it will take the download onto the page itself.

* __JPG__
    * This format is best for pictures made of many colours or rather that have a lot of colour to them, even a landscape phtot of snow has many tones we would be unaware of.

* __GIF | PNG__
    * This format is ideal when there are not many colours or images made up of mostly the same colour in the images

```html
<html>
  <head>
    <title>JPG example</title>
  </head>
  <body>
    <h1>JPG example</h1>
    <p><img src="http://hdimges.com/images/db7_img/snow-landscape-hd-background-wallpaper-27.jpg" alt="snowy landscape demonstrating the uses of JPG" width="150" height="140"></p>
</html>
```

<html>
  <head>
    <title>JPG example</title>
  </head>
  <body>
    <h1>JPG example</h1>
    <p><img src="http://hdimges.com/images/db7_img/snow-landscape-hd-background-wallpaper-27.jpg" alt="snowy landscape demonstrating the uses of JPG" width="150" height="140"></p>
</html>

These kinds of image formats belong to a format known as __BITMAP__. They are made up of lots of tiny squares and the resolution of the image is the number of squares that will fit in a 1 x 1 inch square area, and these squares are what we know as __pixels__.

While it is common for browsers to use 72 ppi, books and magazines and the print industry in general use __dots__ and at a resolution of about __300 dpi__.

It is _crucial_ to note that using an image with a resolution of more than 72 ppi for web browsers will NOT result in a better image quality, only a larger file size, which will mean that the load time is longer.





