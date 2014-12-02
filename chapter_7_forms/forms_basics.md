# FORMS

Forms are things that allow you to collect information from the user be it for shopping or data or search reasons.

The way a form works is as follows.....
* The user fills in the online form and presses a button
* The information is then sent to the server
    * The name of each form control is sent to the server along with the value entered or value selected
* The server then processes the information using a programming language such as PHP/ C#/ VB.net/ Java, AND may store the information in a database
* The server creates a new page to send back to the browser based on the information received

To differentiate between various pieces of inputted data, information is sent from the browser to the server in NAME/VALUE pairs, eg name:USERNAME = MERVE:value

Some examples of FORM CONTROLS include:
Text Input, Text Area, Password Input, Multiple Choices, Checkboxes, Dropdown Menus, Submission Buttons, Subscribe Buttons, and Uploading Options

Forms live inside the ```<form></form>``` element much like the ```<body>``` tags which hold what the user sees.

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

