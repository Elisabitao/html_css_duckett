#THE BASICS OF BOXES

While __px__ will give the designer more control over the size of their product, if measured in __%__ or __em__, it will mean that the design is more flexible.

__%__ means that the box is relative to the containing box/ window.
__em__'s mean that the box is relative to the size of the containing text, which gives the designs the ability to change across multiple devices more easily.

```Min-width/ height``` and ```max-width/ height```...need I say more...

Should your content reach outside the box, you have the overflow option:
```p.one { overflow: hidden; } OR p.one { overflow: scroll; }```

##BOARDER, MARGIN & PADDING

PADDING: The space between the border of a box (Boarder) and any content within it, aka the image used for example
BOARDER: Separates the edge of one box to the other, aka the margin and the padding
MARGIN: The outter box, after the boarder

You can further specify if you want the *top*, *right*, *bottom*, *left* width [NOTICE IT GOES CLOCKWISE] individually as so:
```p.one: { boarder-width: 1px 4px 10px 4px; }```

![](./images_4/css_boxes.png)

Boarder style properties can vary, and be very useful:





















