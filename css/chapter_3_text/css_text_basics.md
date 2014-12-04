#TEXT BASICS IN CSS

Text comes in :

__WEIGHT, STYLE & STRETCH:__ ![](./images_3/weight_style_stretch.png)
```css
p {
  font-family: arial, sans-serif;
  font-weight: bold;
  font-style: italic;
  font-stretch: extended;
}
```
__SERIF & SANS-SERIF:__ ![](./images_3/serif_sans_serif.png)

CSS needs the font-family and the size for text

  * The default for browsers is __16px__*
  * Size comes in either __pixels__ or __percentage__ (remember that pixels are FIXED!)
  * __em__ is the width of the letter 'm' and is used as a point of measure

```css
body {
  font-family: Arial, verdana, sans-serif;
  font-size: 12px; <!-- 75% | 0.75em -->
}

h1 {
  font-size: 200%; <!-- 24px | 1.5em -->
}

h2 {
  font-size: 1.3em; <!-- 18px | 150% -->
}
```
<br>

The ```@font-face``` allows you to use a font even if the user does not have it installed on their own computer/ browser, by allowing you to specify the path to a copy of the font, which will be automatically downloaded if it is not already on the machine:

```css
@font-face {
  font-family: Nexa rust;
  src: url('file:///Users/AnnaMarie/Desktop/im_a_fantastic_developer/html_css_ducket/css/chapter_2_colour/css_test_3.html');
}

h1 {
  font-family: Nexa rust;
}
```
<br>
Different browsers support different font formats so several variations can be required *(fontsquirrel will easily convert them for you: www.fontsquirrel.com/fontface/generator)*

###TIPS AND TRICKS

The __uppercase__, the __lowercase__, and the __capitalize__ text-transform rules:

```css
h3 {
  text-transform: capitalize;
}
```
<br>
Then there is the ```text-decoration``` options

  * __none__: removes any decoration already present
  * __underline__: underlines
  * __overline__: adds a line over the text
  * __line-through__: puts a line through
  * __blink__: animates the text to make it turn off and on, aka, 'blink' effect


















