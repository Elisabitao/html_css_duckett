LIST BASICS
===========

There are 3 main list types of note, the first being ORDERED ```<ol></ol>```, wherein each item is numbered, UNORDERED ```<ul></ul>```, which means the list is simply made up of bullet points, and DEFINITION ```<dl></dl>``` lists.

The third is the most complicated. Definition lists are made up of a set of terms along with the definitions for each of those terms. It uses 3 kinds of tags, the DEFINITON LIST element ```<dl></dl>```, the DEFINITON TERM element ```<dt></dt>```, and the DEFINITION element itself ```<dd></dd>```.

Naturally lists within lists is possible...

```html
<html>
  <title>ordered lists</title>
  <body>
    <h1>BEHOLD THE GLORY OF LISTS</h1>
    <p>A good trilogy that made me think of my own daemon was, aka: <q><em>His Dark Materials</em></q>. Below is the order you should read them in <strong>ROI!</strong>..you loser....<p>
    <ol>
      <li>Northern Lights</li>
      <li>The Subtle Knife</li>
      <li>The Amber Spyglass</li>
    </ol>

    <hr />

    <p>and now an <em>unordered</em> one because I dont know who is my favourite...</p>
    <ul>
      <li>Finn</li>
      <li>Jake</li>
      <li>Marceline</li>
        <ul><h4>minor characters</h4>
          <li>Wormy</li>
          <li>Strachy</li>
          <li>Gunther</li>
        </ul>
      <li>Wormy</li>
      <li>The Ice King</li>
    </ul>

    <hr />

    <p>Last but not least, the <strong>DEFINITION</strong> list...here is a game of colour association:</p>
    <dl>
      <dt>Green</dt>
      <dd>growing, neutral, good, go, plants, strength, earth, stability, energy, wealth, money, greed, ambition, jealousy, harmony</dd>
      <dt>Red</dt>
      <dd>powerful, strong, passion, anger, will power, love, roses, heart, blood, stop, energy, sexuality, desire, danger, wrath</dd>
    </dl>
  </body>
</html>
```

and the results being:

<html>
  <title>ordered lists</title>
  <body>
    <h1>BEHOLD THE GLORY OF LISTS</h1>
    <p>A good trilogy that made me think of my own daemon was, aka: <q><em>His Dark Materials</em></q>. Below is the order you should read them in <strong>ROI!</strong>..you loser....<p>
    <ol>
      <li>Northern Lights</li>
      <li>The Subtle Knife</li>
      <li>The Amber Spyglass</li>
    </ol>

    <hr />

    <p>and now an <em>unordered</em> one because I dont know who is my favourite...</p>
    <ul>
      <li>Finn</li>
      <li>Jake</li>
      <li>Marceline</li>
        <ul><h4>minor characters</h4>
          <li>Wormy</li>
          <li>Strachy</li>
          <li>Gunther</li>
        </ul>
      <li>Wormy</li>
      <li>The Ice King</li>
    </ul>

    <hr />

    <p>Last but not least, the <strong>DEFINITION</strong> list...here is a game of colour association:</p>
    <dl>
      <dt>Green</dt>
      <dd>growing, neutral, good, go, plants, strength, earth, stability, energy, wealth, money, greed, ambition, jealousy, harmony</dd>
      <dt>Red</dt>
      <dd>powerful, strong, passion, anger, will power, love, roses, heart, blood, stop, energy, sexuality, desire, danger, wrath</dd>
    </dl>
  </body>
</html>