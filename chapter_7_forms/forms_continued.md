## FORMS CONTINUED

Forms live inside the <form></form> element much like the <body> tags which hold what the user sees.

Every form element requires an __action__ attribute. Its value is the URL for the page on the server that will receive the information in the form when it is submitted.

```html
<form action="http://www.example.com/subscribe.php" method="get">
  <p></p>
</form>
```

Forms are sent using one of 2 methods, either __*GET*__ or __*POST*__

  * The __GET__ method involves the values from the form, being added onto the end of the URL. It is ideal for __short forms__ (like search boxes), or __when you are retrieving data from the web server__ (aka, NOT information that should be added to or deleted from a database)
  * The __POST__ method sends the values in what are known as HTTP headers. These are ideal for __allowing users to upload a file__, if your form is __very long__, or it contains __sensitive data__, or even __adds information to/ deletes from a database__.

If the method attribute is not used it will be sent using the GET method.

The ```<input>``` element is used to create several different form controls. For eg: ```type="text"``` - which means single line input. The server needs to know which form control the user entered data into, therefore the *name* needs to be clarified. *Size*






