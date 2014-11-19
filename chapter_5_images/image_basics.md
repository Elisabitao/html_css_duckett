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


```html
<html>
  <head>
    <title>Image placement</title>
    <body>
      <h2>Where oh where to go...</h2>
      <img src="https://c2.staticflickr.com/4/3172/2572125432_213489ed3b.jpg" alt="mango pickles galore" title="erm...yum?" height="110" width="150">
      <p>Pickling process in India differs from other regions mainly due to additional spice mixture added to them post anaerobic fermentation. Pickles are main side dishes and many varieties of vegetables are used. However, raw mango or tender mango is the most popular variety of fruit used for pickling. There are multiple variety of mango pickles prepared depending on the region and the spices used but, broadly there are two types of - whole baby mango pickle or cut mango pickle. Whole baby mango pickle is a traditional variety very popular in Southern India and uses baby mangoes that are few weeks old. There are special varieties of mangoes specifically used just for pickling and they are never consumed as ripe fruit. Baby mangoes are pickled and added with spice mixture in a very careful process which ensures pickles are preserved for years.</p>

      <p><img src="https://c2.staticflickr.com/4/3172/2572125432_213489ed3b.jpg" alt="mango pickles galore" title="erm...yum?" height="110" width="150">Pickling process in India differs from other regions mainly due to additional spice mixture added to them post anaerobic fermentation. Pickles are main side dishes and many varieties of vegetables are used. However, raw mango or tender mango is the most popular variety of fruit used for pickling. There are multiple variety of mango pickles prepared depending on the region and the spices used but, broadly there are two types of - whole baby mango pickle or cut mango pickle. Whole baby mango pickle is a traditional variety very popular in Southern India and uses baby mangoes that are few weeks old. There are special varieties of mangoes specifically used just for pickling and they are never consumed as ripe fruit. Baby mangoes are pickled and added with spice mixture in a very careful process which ensures pickles are preserved for years.</p>

      <p>Pickling process in India differs from other regions mainly due to additional spice mixture added to them post anaerobic fermentation. Pickles are main side dishes and many varieties of vegetables are used. However, raw mango or tender mango is the most popular variety of fruit used for pickling. There are multiple variety of mango pickles prepared depending on the region and the spices used but, broadly there are two types of <img src="https://c2.staticflickr.com/4/3172/2572125432_213489ed3b.jpg" alt="mango pickles galore" title="erm...yum?" height="110" width="150">- whole baby mango pickle or cut mango pickle. Whole baby mango pickle is a traditional variety very popular in Southern India and uses baby mangoes that are few weeks old. There are special varieties of mangoes specifically used just for pickling and they are never consumed as ripe fruit. Baby mangoes are pickled and added with spice mixture in a very careful process which ensures pickles are preserved for years.</p>

      <p><img src="https://c2.staticflickr.com/4/3172/2572125432_213489ed3b.jpg" alt="mango pickles galore" title="erm...yum?" height="110" width="150" align="left" />Pickling process in India differs from other regions mainly due to additional spice mixture added to them post anaerobic fermentation. Pickles are main side dishes and many varieties of vegetables are used. However, raw mango or tender mango is the most popular variety of fruit used for pickling. There are multiple variety of mango pickles prepared depending on the region and the spices used but, broadly there are two types of - whole baby mango pickle or cut mango pickle. Whole baby mango pickle is a traditional variety very popular in Southern India and uses baby mangoes that are few weeks old. There are special varieties of mangoes specifically used just for pickling and they are never consumed as ripe fruit. Baby mangoes are pickled and added with spice mixture in a very careful process which ensures pickles are preserved for years.</p>

      <p><img src="https://c2.staticflickr.com/4/3172/2572125432_213489ed3b.jpg" alt="mango pickles galore" title="erm...yum?" height="110" width="150" align="right" />Pickling process in India differs from other regions mainly due to additional spice mixture added to them post anaerobic fermentation. Pickles are main side dishes and many varieties of vegetables are used. However, raw mango or tender mango is the most popular variety of fruit used for pickling. There are multiple variety of mango pickles prepared depending on the region and the spices used but, broadly there are two types of - whole baby mango pickle or cut mango pickle. Whole baby mango pickle is a traditional variety very popular in Southern India and uses baby mangoes that are few weeks old. There are special varieties of mangoes specifically used just for pickling and they are never consumed as ripe fruit. Baby mangoes are pickled and added with spice mixture in a very careful process which ensures pickles are preserved for years.</p>

      <p><img src="https://c2.staticflickr.com/4/3172/2572125432_213489ed3b.jpg" alt="mango pickles galore" title="erm...yum?" height="110" width="150" align="top" />Pickling process in India differs from other regions mainly due to additional spice mixture added to them post anaerobic fermentation. Pickles are main side dishes and many varieties of vegetables are used. However, raw mango or tender mango is the most popular variety of fruit used for pickling. There are multiple variety of mango pickles prepared depending on the region and the spices used but, broadly there are two types of - whole baby mango pickle or cut mango pickle. Whole baby mango pickle is a traditional variety very popular in Southern India and uses baby mangoes that are few weeks old. There are special varieties of mangoes specifically used just for pickling and they are never consumed as ripe fruit. Baby mangoes are pickled and added with spice mixture in a very careful process which ensures pickles are preserved for years.</p>

      <p><img src="https://c2.staticflickr.com/4/3172/2572125432_213489ed3b.jpg" alt="mango pickles galore" title="erm...yum?" height="110" width="150" align="middle" />Pickling process in India differs from other regions mainly due to additional spice mixture added to them post anaerobic fermentation. Pickles are main side dishes and many varieties of vegetables are used. However, raw mango or tender mango is the most popular variety of fruit used for pickling. There are multiple variety of mango pickles prepared depending on the region and the spices used but, broadly there are two types of - whole baby mango pickle or cut mango pickle. Whole baby mango pickle is a traditional variety very popular in Southern India and uses baby mangoes that are few weeks old. There are special varieties of mangoes specifically used just for pickling and they are never consumed as ripe fruit. Baby mangoes are pickled and added with spice mixture in a very careful process which ensures pickles are preserved for years.</p>

      <p><img src="https://c2.staticflickr.com/4/3172/2572125432_213489ed3b.jpg" alt="mango pickles galore" title="erm...yum?" height="110" width="150" align="bottom" />Pickling process in India differs from other regions mainly due to additional spice mixture added to them post anaerobic fermentation. Pickles are main side dishes and many varieties of vegetables are used. However, raw mango or tender mango is the most popular variety of fruit used for pickling. There are multiple variety of mango pickles prepared depending on the region and the spices used but, broadly there are two types of - whole baby mango pickle or cut mango pickle. Whole baby mango pickle is a traditional variety very popular in Southern India and uses baby mangoes that are few weeks old. There are special varieties of mangoes specifically used just for pickling and they are never consumed as ripe fruit. Baby mangoes are pickled and added with spice mixture in a very careful process which ensures pickles are preserved for years.</p>
    </body>
  </head>
</html>
```

Here is what one would see from a browsers perspective:

<html>
  <head>
    <title>Image placement</title>
    <body>
      <h2>Where oh where to go...</h2>
      <img src="https://c2.staticflickr.com/4/3172/2572125432_213489ed3b.jpg" alt="mango pickles galore" title="erm...yum?" height="110" width="150">
      <p>Pickling process in India differs from other regions mainly due to additional spice mixture added to them post anaerobic fermentation. Pickles are main side dishes and many varieties of vegetables are used. However, raw mango or tender mango is the most popular variety of fruit used for pickling. There are multiple variety of mango pickles prepared depending on the region and the spices used but, broadly there are two types of - whole baby mango pickle or cut mango pickle. Whole baby mango pickle is a traditional variety very popular in Southern India and uses baby mangoes that are few weeks old. There are special varieties of mangoes specifically used just for pickling and they are never consumed as ripe fruit. Baby mangoes are pickled and added with spice mixture in a very careful process which ensures pickles are preserved for years.</p>

      <p><img src="https://c2.staticflickr.com/4/3172/2572125432_213489ed3b.jpg" alt="mango pickles galore" title="erm...yum?" height="110" width="150">Pickling process in India differs from other regions mainly due to additional spice mixture added to them post anaerobic fermentation. Pickles are main side dishes and many varieties of vegetables are used. However, raw mango or tender mango is the most popular variety of fruit used for pickling. There are multiple variety of mango pickles prepared depending on the region and the spices used but, broadly there are two types of - whole baby mango pickle or cut mango pickle. Whole baby mango pickle is a traditional variety very popular in Southern India and uses baby mangoes that are few weeks old. There are special varieties of mangoes specifically used just for pickling and they are never consumed as ripe fruit. Baby mangoes are pickled and added with spice mixture in a very careful process which ensures pickles are preserved for years.</p>

      <p>Pickling process in India differs from other regions mainly due to additional spice mixture added to them post anaerobic fermentation. Pickles are main side dishes and many varieties of vegetables are used. However, raw mango or tender mango is the most popular variety of fruit used for pickling. There are multiple variety of mango pickles prepared depending on the region and the spices used but, broadly there are two types of <img src="https://c2.staticflickr.com/4/3172/2572125432_213489ed3b.jpg" alt="mango pickles galore" title="erm...yum?" height="110" width="150">- whole baby mango pickle or cut mango pickle. Whole baby mango pickle is a traditional variety very popular in Southern India and uses baby mangoes that are few weeks old. There are special varieties of mangoes specifically used just for pickling and they are never consumed as ripe fruit. Baby mangoes are pickled and added with spice mixture in a very careful process which ensures pickles are preserved for years.</p>

      <p><img src="https://c2.staticflickr.com/4/3172/2572125432_213489ed3b.jpg" alt="mango pickles galore" title="erm...yum?" height="110" width="150" align="left" />Pickling process in India differs from other regions mainly due to additional spice mixture added to them post anaerobic fermentation. Pickles are main side dishes and many varieties of vegetables are used. However, raw mango or tender mango is the most popular variety of fruit used for pickling. There are multiple variety of mango pickles prepared depending on the region and the spices used but, broadly there are two types of - whole baby mango pickle or cut mango pickle. Whole baby mango pickle is a traditional variety very popular in Southern India and uses baby mangoes that are few weeks old. There are special varieties of mangoes specifically used just for pickling and they are never consumed as ripe fruit. Baby mangoes are pickled and added with spice mixture in a very careful process which ensures pickles are preserved for years.</p>

      <p><img src="https://c2.staticflickr.com/4/3172/2572125432_213489ed3b.jpg" alt="mango pickles galore" title="erm...yum?" height="110" width="150" align="right" />Pickling process in India differs from other regions mainly due to additional spice mixture added to them post anaerobic fermentation. Pickles are main side dishes and many varieties of vegetables are used. However, raw mango or tender mango is the most popular variety of fruit used for pickling. There are multiple variety of mango pickles prepared depending on the region and the spices used but, broadly there are two types of - whole baby mango pickle or cut mango pickle. Whole baby mango pickle is a traditional variety very popular in Southern India and uses baby mangoes that are few weeks old. There are special varieties of mangoes specifically used just for pickling and they are never consumed as ripe fruit. Baby mangoes are pickled and added with spice mixture in a very careful process which ensures pickles are preserved for years.</p>

      <p><img src="https://c2.staticflickr.com/4/3172/2572125432_213489ed3b.jpg" alt="mango pickles galore" title="erm...yum?" height="110" width="150" align="top" />Pickling process in India differs from other regions mainly due to additional spice mixture added to them post anaerobic fermentation. Pickles are main side dishes and many varieties of vegetables are used. However, raw mango or tender mango is the most popular variety of fruit used for pickling. There are multiple variety of mango pickles prepared depending on the region and the spices used but, broadly there are two types of - whole baby mango pickle or cut mango pickle. Whole baby mango pickle is a traditional variety very popular in Southern India and uses baby mangoes that are few weeks old. There are special varieties of mangoes specifically used just for pickling and they are never consumed as ripe fruit. Baby mangoes are pickled and added with spice mixture in a very careful process which ensures pickles are preserved for years.</p>

      <p><img src="https://c2.staticflickr.com/4/3172/2572125432_213489ed3b.jpg" alt="mango pickles galore" title="erm...yum?" height="110" width="150" align="middle" />Pickling process in India differs from other regions mainly due to additional spice mixture added to them post anaerobic fermentation. Pickles are main side dishes and many varieties of vegetables are used. However, raw mango or tender mango is the most popular variety of fruit used for pickling. There are multiple variety of mango pickles prepared depending on the region and the spices used but, broadly there are two types of - whole baby mango pickle or cut mango pickle. Whole baby mango pickle is a traditional variety very popular in Southern India and uses baby mangoes that are few weeks old. There are special varieties of mangoes specifically used just for pickling and they are never consumed as ripe fruit. Baby mangoes are pickled and added with spice mixture in a very careful process which ensures pickles are preserved for years.</p>

      <p><img src="https://c2.staticflickr.com/4/3172/2572125432_213489ed3b.jpg" alt="mango pickles galore" title="erm...yum?" height="110" width="150" align="bottom" />Pickling process in India differs from other regions mainly due to additional spice mixture added to them post anaerobic fermentation. Pickles are main side dishes and many varieties of vegetables are used. However, raw mango or tender mango is the most popular variety of fruit used for pickling. There are multiple variety of mango pickles prepared depending on the region and the spices used but, broadly there are two types of - whole baby mango pickle or cut mango pickle. Whole baby mango pickle is a traditional variety very popular in Southern India and uses baby mangoes that are few weeks old. There are special varieties of mangoes specifically used just for pickling and they are never consumed as ripe fruit. Baby mangoes are pickled and added with spice mixture in a very careful process which ensures pickles are preserved for years.</p>
    </body>
  </head>
</html>









