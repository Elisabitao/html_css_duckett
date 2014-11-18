# MARKUP - semantic

Semantic markup will be covered in this section. These are tags that are more useful to the browser and other programmes for they get to read these tags and get extra information on what is the desired outcome.
```<strong></strong>``` These are words that the browser knows to place a 'STRONG' emphasis on, and are by default usually shown in bold or a screen reader would emphasize.

```<em></em>``` Represents EMPHASIS and have the similar if not same attributes as strong, only they are shown in italic rather than bold.

BLOCKQUOTE is best for placing quotations around a paragraph or large section of text ```</blockquote>```

```<q></q>``` This is used for smaller sections of text that needs to have QUOTATION marks

ABBREVIATIONS ```<abbr></abbr>``` are used for acronyms as well though in HTML4 they were marked as separate (which is no longer the case)

If a piece of work is to be referenced then a ```<cite></cite>``` element should be used. Many people use it to refer to or rather CITE names as well as it was allowed in HTML4 but it is best avoided in HTML5.

It may seem odd to use ```<dfn></dfn>``` in your code if it does not markedly change the codes appearance but it does give the browser more information and that is what counts so use DEFINE.

The ADDRESS element is self explanatory, and usually formats the text into italic ```<address></address>```

```<ins></ins>``` INSERT shows where new content has been added, and usually shows itself as being underlined for emphasis

```<del></del>``` is for DELETED content and will demonstrate itself by having a line drawn through it

```<s></s>``` is for when content that is no longer relevant but should not be deleted, like a discounted price

delHere is another example showing what I have learnt:

```html
<html>
  <title>Semantic Markup</title>
    <body>
      <p>This is where </blockquote>I will put <strong>strong emphasis</strong> on <q>my work</q> <br />and this is where I will put just <em>emphasis</em> on what Im writing about</p>
      <hr />
      <p>Now I have to think of an abbreviation...how about <q>I always use a <abbr title="Universal Serial Bus">USB</abbr> for carrying my work around</q>. A <dfn>USB</dfn> is a small microchip that can store digital formats of documents <ins>and music</ins> <del>and such<del>. This is where I need to reference something like the fact that <cite>Game of Thrones</cite> by <em>George R. R. Martin</em> is <strong>awesome</strong>.</p>
      <hr />
      <address>
      <p>For more information please go to these points of enquiry:<br /><s>blahblah@bored.com</s> comeseeme@gmail.com<br />123 Come See Me Road, London Town</p>
      </address>
    </body>
</html>
```

and Here is the real thing:

<html>
  <title>Semantic Markup</title>
    <body>
      <p>This is where </blockquote>I will put <strong>strong emphasis</strong> on <q>my work</q> <br />and this is where I will put just <em>emphasis</em> on what Im writing about</p>
      <hr />
      <p>Now I have to think of an abbreviation...how about <q>I always use a <abbr title="Universal Serial Bus">USB</abbr> for carrying my work around</q>. A <dfn>USB</dfn> is a small microchip that can store digital formats of documents <ins>and music</ins> <del>and such<del>. This is where I need to reference something like the fact that <cite>Game of Thrones</cite> by <em>George R. R. Martin</em> is <strong>awesome</strong>.</p>
      <hr />
      <address>
      <p>For more information please go to these points of enquiry:<br /><s>blahblah@bored.com</s> comeseeme@gmail.com<br />123 Come See Me Road, London Town</p>
      </address>
    </body>
</html>