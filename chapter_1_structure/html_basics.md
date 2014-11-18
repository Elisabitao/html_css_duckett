# HTML BASICS

## HYPER TEXT MARKUP LANGUAGE

Structure is key, the headings and subheading denote hierarchy. HTML code itself is usually made up of elements aka 1 or 2 tags, such as ```<h1></h1>```. The tags act like containers.

Attribute elements:
They tell us more about the HTML element/ whats inside the tags, and are often made up of 2 parts: NAME and VALUE.
  eg. ```<p lang="eng-us">```These paragraphs will be in English US because that is standard for code```</p>```

The layout of ANY html page is as follows =

  HEAD || denotes what will NOT be seen on the page, and can contain useful information for the coder, think of it as the 'backstage area'...it should have links to CSS stylesheets and information that google reads...but title will show in the 'tab'
  TITLE || Whats written in the 'tab'
  BODY || Whats displayed on the web page itself (the stage)

  for example:

```html
<html>
  <head>
    <title>The title of a page is displayed in the tabs section or title bar</title>
  </head>
  <body>
    <h1>Anything displayed here in the body will be displayed on the browser</h1>
      <p>The 'head' is a separate thing altogether</p>
  </body>
</html>
```