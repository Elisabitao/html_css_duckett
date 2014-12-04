#MARKUP BASICS

Because there have been several versions of HTML all documents start with __DOCTYPE__ declaration to tell the browser what version it is dealing with. WHile not entirely necessary, it is very good practise.

Here are some examples in order to recognise what you are working with:

```html
<!DOCTYPE html><!--  HTML5 -->

<!DOCTYPE html PUBLIC
  "-//W3C//DTD HTML 4.01 Transitional//EN"
  "http://www.w3.org/TR/html4/loose.dtd"><!--  HTML4 -->

<!DOCTYPE html PUBLIC
  "-//W3C//DTD XHTML 1.0 Transitional//EN"
  "http://www.w3.org/TR/Xhtml1/DTD/xhtml1-transitional.dtd"><!--  Transitional XHTML --> 1.0

<!DOCTYPE html PUBLIC
  "-//W3C//DTD XHTML 1.0 Strict//EN"
  "http://www.w3.org/TR/Xhtml1/DTD/xhtml1-strict.dtd"> <!-- Strict XHTML 1.0 -->

<?xml version="1.0" ?> <!-- XML Declaration -->
```

###ID ATTRIBUTE

This is the attribute that uniquely identifies that element from all other elements. The value should ALWAYS start with either a __letter__ or an __underscore__ and of course, should never be the same as any other ID.

By giving an element an ID it means that it enables you to uniquely style that particular element in CSS from any other!

```html
<!DOCTYPE html>
<html>
  <head>
    <title>ID example</title>
    <body>
      <h1>ID examples</h1>
      <p>Every HTML element can carry the id attribute. It is used to uniquely identify that element from other elements on the page. Its value should start with a letter or an underscore (not a number or any other character.</p>
      <p id="java.info">If you go on to learn about JavaScript (a language that allows you to add interactivity to your pages), id attributes can be used to allow the script to work with that particular element.</p>
    </body>
  </head>
</html>
```
<There is no 'live' example here because there is no CSS to show/do but the principal is fine>

###CLASS ATTRIBUTE

Sometimes it is more practical to have a __class__ rather than an ID, which means that several elements can be identified rather than just the one.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>ID example</title>
    <body>
      <h1>ID examples</h1>
      <p class="important html">Every HTML element can carry the id attribute. It is used to uniquely identify that element from other elements on the page. Its value should start with a letter or an underscore (not a number or any other character.</p>
      <p id="java.info">If you go on to learn about JavaScript (a language that allows you to add interactivity to your pages), id attributes can be used to allow the script to work with that particular element.</p>
      <p class="important CSS">If you would like to indicate that an element belongs to several classes, you can separate class names with a space.</p>
    </body>
  </head>
</html>
```
*These attributes only change the appearance if there is a CSS rule that indicates it/ they should be displayed differently.*

####BLOCK ELEMENTS

Block elements always start on a new line automatically, some examples include:

   * Headers ```<h1></h1>```
   * Paragraphs ```<p></p>```
   * Unordered lists
             ```<ul>
                 <li></li>
                 <li></li>
             ```</ul>

####INLINE ELEMENTS

These are elements that always appear to continue on the same line:

   * Anchor (link) ```<a></a>```
   * Bold ```<b></b>```
   * Emphasis ```<em></em>```
   * Image ```<img></img>```

####GROUPING

Grouping elements and text in blacks of code makes sense for easy reading/ clarification. The ```<div></div>``` is the most common one, and will automatically make the elements start on a new line. Sometimes a ```<div>``` may need an ```<id>``` just to make things clearer.

The ```<span></span>``` element is used for the same reasons as the div, the main difference being that it is *in line* rather than a 'section'. The main reason this is useful is so that we can edit a specific part of a paragraph with CSS. It usually comes with a *class* to not only more clearly identify the CSS styles used but to also explain the purpose of the ```<span>```.

```html
<!DOCTYPE html>
<html>
  <head>
    <title></title>
  </head>
  <body>
    <p>The most common reason why people use elements is so that they can <span class="example"> control the appearance of the content of these elements </span> using CSS.</p>
  </body>
</html>
```

####IFRAMES

DONT BOTHER. __NO BODY LIKES THEM__.

####META

__Put this at the top of EVERY html file in the ```<head>``` section: ```<meta charset=UTF-8>```__

The ```<meta>``` element is placed inside the ```<head>``` element, and contains information about the web page. It is most useful for search engines as it contains info about your page, who created it, if its time sensitive, etc. __Name__ and __Content__ tend to be the most common uses for it.

The ```<meta name="">``` attribute can be anything, but some common examples are *Description*: of the page, *Keywords*: list of words associated/ one might use to search for the web site, and *Robots*: indicates whether search engines should add this page to their search results or not (a value of  *'no index'* can be used if not, and *'no follow'* if they can use it but not any pages that it links to).

```html
<!DOCTYPE html>
  <html>
    <head>
      <meta charset=UTF-8>
      <title>Info about your pages</title>
      <meta name="description"
        content="An essay on information about your pages and html and search engines" />
      <meta name="keywords"
        content="html, info, information, search engines, browsers" />
      <meta name="robots"
        content="no follow" />
    </head>
    <body>
      <h1>Information on your pages:</h1>
      <p>In the first line of the example on the opposite page, you can see a meta element where the name attribute indicates an intention to specify a description for the page. The content attribute is where this description is actually specified.</p>
    </body>
  </html>
```

The meta also uses the ```<meta http-equiv>``` and content attributes in pairs.
*Author*: defines the author, *Pragma*: prevents the browser from caching the page, and *Expires*: is used to indicate when the page should expire - the date must be specified!.

```html
  <!DOCTYPE html>
    <html>
      <head>
        <meta charset=UTF-8>
        <title>Info about your pages</title>
        <meta name="description"
          content="An essay on information about your pages and html and search engines" />
        <meta name="keywords"
          content="html, info, information, search engines, browsers" />
        <meta name="robots"
          content="no follow" />
        <meta http-quiv="author"
          content="Merve Silk" />
        <meta http-quiv="pragma"
          content="no-cache" />
        <meta http-quiv="expires"
          content="Wed, 13 Jun 2014 23:59:59 GMT" />
      </head>
      <body>
        <h1>Information on your pages:</h1>
        <p>In the first line of the example on the opposite page, you can see a meta element where the name attribute indicates an intention to specify a description for the page. The content attribute is where this description is actually specified.</p>
      </body>
    </html>
```











