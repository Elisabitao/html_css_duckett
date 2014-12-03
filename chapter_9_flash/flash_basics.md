#FLASH, VIDEO, AUDIO BASICS

Flash is essentially used to create animations.

When a *Flash file* is created it is saved with the extension: __.fla__, if you want to use said file on your web page, then the extension changes to: __.swf__.

The most popular way of adding Flash to a web page is with JavaScript. There are several scripts that allow you to do this without needing in-depth understanding of the language. For example, *__SWFObject__*.

One of the advantages of using this technique is that if you have a browser that does not support Flash then you have alternative content to choose from such as showing a still from the animation/ film, or a written description.

This technique uses a ```<div>``` element and ID for clarification.

```html
<!DOCTYPE html>
  <html>
    <head>
      <title>Adding a flash film</title>
      <script type="text/javascript"
        src="http://ajax.googleapis.com/ajax/libs/swfobject/2.2/swfobject.js"></script> <!-- this example is hosted on google, here it is showing the source to make the argument (shown in the the second script) work. The type attribute is used to indicate that the script inside is written in javascript, and the src shows the browser where to find it  -->
      <script type="text/javascript">swfobject.embedSWF("http://www.htmlandcssbook.com/code-samples/chapter-09/flash/bird.swf", "bird", "400", "300", "8.0.0");</script> <!-- this script element tells the browser it is a flash film as well aswhich element it should replace. this element is actually telling the SWFObject script 5 pieces of information - the location of the file:http://www.htmlandcssbook.com/code-samples/chapter-09/flash/bird.swf, the element it should replace: bird (specified by the div id), the width and height: 400/ 300, and the minimum version the flash player needs to view the movie: 8 -->
    </head>
    <body>
      <h1>Flash example</h1>
      <div id="bird"><p>Here is the video (I hope...) of a bird taking a shower</p></div>
    </body>
  </html>
```


