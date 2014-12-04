MARKUP - structural
======

Markup is another term for tags or elements in HTML. There are 2 kinds, 'structural' and 'semantic'.
  STRUCTURAL : elements that are used to describe both headings and paragraphs
  SEMANTIC : provide extra information such as on the emphasis in a sentence etc

  Here Structural will be covered in detail.

HTML has 6 basic heading sizes, like 'paper', the lower the number the larger it is - aka ```<h1></h1>``` is the ```<h1>BIGGEST</h1>``` with ```<h6></h6>``` being the smallest.

Paragraphs use the ```<p></p>``` tags and by default will start on a new line after each other even if in the code itself is back to back, provided they have their close.

```<b></b>``` This is how we make text BOLD or mark the text to be represented visually in a different way.

The same goes for ITALIC ```<i></i>```.

```<sup></sup>``` is used to contain characters that should be superscript like dates or suffixes.

```<sub></sub>``` 'Sub' is for subscript, most often used for things like footnotes.

Empty Elements:

These are elements that have no closing tag and are often (or at least should be) identified by their space and forward slash....many coders miss these out but it is best practice to keep it in.

Coders often use the fact that when a browser sees more than one space or line break etc it treats it as if it were only one anyway. This is called WHITE SPACE COLLAPSING and coders use it to their advantage when it comes to making their work more readable. To get around this, if such is your intent, you would use the LINE BREAK TAG <br />

Whereas the <hr /> tag will create a divide or a HORIZONTAL RULE as it it better known as


This is an example of some terminal code which uses all of the above elements:

```html
<html>
  <head>
    <title>Structural Markup</title>
  </head>
    <body>
      <h1>One giant header coming up!</h1>
      <hr />
      <h6>and the smallest just for show</h6>

      <p>paragraph to be placed here oh me oh my, but what is a word if it is not <b>bold and obvious?</b>, it matters not, for we can at least use <i>italics in its stead</i> is that not so?</p>


      <p>Here we shall show what uses              superscript can have, on the date 17<sup>th</sup> while also showing how subscript can work as well, <br />like in H<sub>2</sub>O....<br />aint this all fun and games....</p>
    </body>
</html>
```

and this is how is looks on a webpage:

<html>
  <head>
    <title>Structural Markup</title>
  </head>
    <body>
      <h1>One giant header coming up!</h1>
      <hr />
      <h6>and the smallest just for show</h6>

      <p>paragraph to be placed here oh me oh my, but what is a word if it is not <b>bold and obvious?</b>, it matters not, for we can at least use <i>italics in its stead</i> is that not so?</p>


      <p>Here we shall show what uses superscript can have, on the date 17<sup>th</sup> while also showing how subscript can work as well, <br />like in H<sub>2</sub>O....<br />aint this all fun and games....</p>
    </body>
</html>

