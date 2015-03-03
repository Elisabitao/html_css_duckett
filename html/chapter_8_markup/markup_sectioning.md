# How to use Sectioning Elements in HTML5

##ARTICLE element
####*and the HEADER / FOOTER / TIME elements that work with it*

The article element ```<article></article>``` is clearly for __Articles__, but also for __Blog posts__, __Forum posts__, or even __User Comments__, and can be nested within each other.

The publish date for the Blog/ Forum posts leads us naturally to not only use a ```<header></header> AND/OR <footer></footer>``` element, but ```<time></time>``` tags as well.

Header elements should be used as a container for introductory content. Footers typically contain the *author*, *copywrite information*, *contact info*, and *links to terms of use*. Both are __required__ to be about said article (or 'sections') and both can have several footer/header elements in one document.

```html
<!DOCTYPE html>
  <html>
    <head>
      <meta charset=UTF-8>
      <title></title>
    </head>
    <body>      <!--This is the 'Article Style' of <article></article>, with 'User Comments'-->
      <article>
        <header>
          <h1>WWF Ideals</h1>
          <p>[Published: <time pubdate="pubdate">Friday 13th 2015</time>]</p>
        </header>
        <p id="WWFideals">We will at all times seek to minimize the environmental impact (especially any adverse impact) of our activities, and make sure that they always comply with all environmental protection legislation. In our daily lives, both at work and in our private time, we will practice what we preach by doing all we can to reduce pollution and waste, and wherever possible use renewable and recyclable materials. And we will encourage all those with whom we interact to do the same.</p>
        <section>
          <h2>Comments<h2>
            <article>
              <header>
                <h3>Posted By: Number 1 WWF fan</h3>
                <p><time pubdate datetime="2009-10-10t19:10-08:00">~1 hour ago</time></p>
              </header>
              <p>I am the number one fan of WWF and I think the ethics are great!</p>
            </article>
            <article>
              <header>
                <h3>Posted By: LippyPops99</h3>
                <p><time pubdate datetime="2009-10-10t19:10-08:00">~1 hour ago</time></p>
              </header>
              <p>No you're not I am!</p>
            </article>
        </section>
      </article>
    </body>
  </html>
```

###MAIN element

The 'main' element ```<main role="main"></main>``` should be used for the main content of your webpage. All this content should be UNIQUE to this particular page, and therefore should not appear on any other part of the site. Any content that is displayed on multiple pages (such as links, logos and search boxes) should not be inside this element.

*use the ARIA main role="" tag so that screenreaders that don't support the main tag understand its significance*

```html
<!DOCTYPE html>
  <html>
    <head>
      <meta charset=UTF-8>
      <title></title>
    </head>
    <body>
      <main role="main">
        <article>
          <h1>Guitars</h1>
          <p id="guitar">guitars are cool etc...</p>
        </article>
      </main>
    </body>
  </html>
```

















      <article>
        <h1>WWF Fraud and Prevention</h1>
        <p id="WWFideals">WWF’s principle is to take a “zero tolerance” approach towards fraud and corruption in its offices around the world. The WWF Network follows common standards on the prevention of fraud and corruption. This is WWF International’s policy on the prevention of fraud and corruption. It is followed by WWF International and all the Programme Offices which report into it.</p>
      </article>
        <footer>
          <p>Posted By: Mervé Silk</p>
          <p>Contact info: <a href="mailto:mervesilksaddress@mail.com">Merve's Email Address</a>.</p>
        </footer>









