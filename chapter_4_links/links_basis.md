LINKS - BASICS
==============

Links are the defining feature of the web, as they allow us to move from one page to another, enabling the very idea of browsing or surfing.

The most common links we will come across are links that take us:
  from one website to another
  from one page of a particular website to another within its domain
  a link that sends us to another part of the same page
  links that open up an entirely new browser window
  links that start up your email and address a new email to someone aka the link clicked

Links are createed using the <a href=""></a>, and users specify where they want to go by using the "href" attribute.

Broken down it looks like this:

<a href="http://www.bbc.co.uk">BBC</a>

<a href="http://www.bbc.co.uk"> --- this is the opeing link tag
 BBC --- this is what the user clicks on/ sees
</a> --- end of code/ closing tag

The URL - UNIVERSAL RESOURCE LOCATOR - is the web address, a domain name followed by the path to a specific page

Links can use a shorthand when linking from one page to another in the same domain, this is called a RELATIVE URL.

```html
<html>
  <title>Links</title>
  <body>
    <h3>Links and what nots</h3>

    <p>Here are links to individual sites:
      <ul>
        <li><a href="http://www.deviantart.com/">Deviant Art</a></li>
        <li><a href="http://www.youtube.com/">YouTube</a></li>
        <li><a href="https://www.stumbleupon.com/">Stumble Upon</a></li>
      </ul>
    </p>

    <hr />

    <p>Here is a link to the BBC and its subsections:
      <ol>
        <li><a href="http://www.bbc.co.uk/">BBC HOMEPAGE</a></li>
                <!-- these links below seem not to work....why? -->
        <li><a href="iplayer.html">BBC iPlayer</a></li>
        <li><a href="weather.html">BBC Weather</a></li>
      </ol>
    </p>
  </body>
</html>
```

<html>
  <title>Links</title>
  <body>
    <h3>Links and what nots</h3>

    <p>Here are links to individual sites:
      <ul>
        <li><a href="http://www.deviantart.com/">Deviant Art</a></li>
        <li><a href="http://www.youtube.com/">YouTube</a></li>
        <li><a href="https://www.stumbleupon.com/">Stumble Upon</a></li>
      </ul>
    </p>

    <hr />

    <p>Here is a link to the BBC and its subsections:
      <ol>
        <li><a href="http://www.bbc.co.uk/">BBC HOMEPAGE</a></li>
                <!-- these links below seem not to work....why? -->
        <li><a href="iplayer.html">BBC iPlayer</a></li>
        <li><a href="weather.html">BBC Weather</a></li>
        <li><a href="news.html">BBC News</a></li>
      </ol>
    </p>
  </body>
</html>

