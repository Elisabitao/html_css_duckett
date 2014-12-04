####FILE INPUT BOX

This means using the ```<input>``` tag again, and making the ```type="file"```.This means that it will create a text box PLUS a 'browse button' for the user to search for the desired file.

When allowing users to upload a file, the GET method MUST be __POST__!!!

```html
<html>
  <head>
    <title>Uploading Songs</title>
  </head>
  <body>
    <form action="http://www.example.com/subscribe.php" method="post">
      <p>Upload your favourite song in MP3 format:</p>
      <input type="file" name="user's song" />
      <input type="submit" name="Submit" value="Upload button" />
    </form>
  </body>
</html>
```
    <form action="http://www.example.com/subscribe.php" method="post">
      <p>Upload your favourite song in MP3 format:</p>
      <input type="file" name="user's song" />
      <input type="submit" name="Submit" value="Upload button" />
    </form>

####IMAGE BUTTON

Again the element is ```<input type="image">``` to use an actual image for a submit button. The rest of the information required works like the normal image attributes:

```html
<form action="http://www.example.com/subscribe.php">
  <input type="text" name="email" />
  <input type="image" src="http://www.motherswhowork.co.uk/wp-content/uploads/2013/08/orange-submission-button.png" alt="orange submit button" width="80" height="30">
</form>
```
<form action="http://www.example.com/subscribe.php">
  <input type="text" name="email" />
  <input type="image" src="http://www.motherswhowork.co.uk/wp-content/uploads/2013/08/orange-submission-button.png" alt="orange submit button" width="80" height="30">
</form>

####BUTTON

The 'Button' element was invented to give greater control over what and how the buttons appeared, aka, you can use this tag to combine text and images, the layout isn't perfect, but that is why this should ideally be done in CSS:

```html
<form action="http://www.example.com/subscribe.php">
  <button><img src="http://upload.wikimedia.org/wikipedia/commons/1/10/Crystal_Project_Add_group.png" alt="add people" width="50" height="50">ADD PEOPLE</button>
</form>
```
<form action="http://www.example.com/subscribe.php">
  <button><img src="http://upload.wikimedia.org/wikipedia/commons/1/10/Crystal_Project_Add_group.png" alt="add people" width="50" height="50">ADD PEOPLE</button>
</form>

####LABELING FORM CONTROLS

Each from control should have its own <label> element as this makes the form accessible to vision-impaired users. It can be used in 2 ways:

  * Wrap around both the text description and the form input
  * Be kept separate from the control and use the for attribute to indicate which form control it is a label for

```html
<form action="http://www.example.com/subscribe.php">
  <label>Age: <input type="text" name="age" /></label>
  <br />
    <label for="female">Female</label>
    <input id="female" type="radio" name="gender" value="F">
    <label for="male">Male</label>
    <input id="male" type="radio" name="gender" value="m">
</form>
```
<form action="http://www.example.com/subscribe.php">
  <label>Age: <input type="text" name="age" /></label>
  <br />
    <label for="female">Female</label>
    <input id="female" type="radio" name="gender" value="F">
    <label for="male">Male</label>
    <input id="male" type="radio" name="gender" value="m">
</form>

####GROUPING FORM ELEMENTS

To group related form controls you need to use the ```<fieldset>``` element. Normally the ```<legend>``` element comes directly after in order to explain the commonality of the grouping *bare in mind this will create a boarder around your questions:

```html
<form action="http://www.example.com/subscribe.php">
  <fieldset>
    <legend>Contact Details</legend>
      </label>Name:
      <input type="text" name="name" /><label><br />
      </label>Mobile:
      <input type="text" name="mobile" /><label><br />
      </label>Email:
      <input type="text" name="email" /><label><br />
  </fieldset>
</form>
```
<form action="http://www.example.com/subscribe.php">
  <fieldset>
    <legend>Contact Details</legend>
      </label>Name:
      <input type="text" name="name" /><label><br />
      </label>Mobile:
      <input type="text" name="mobile" /><label><br />
      </label>Email:
      <input type="text" name="email" /><label><br />
  </fieldset>
</form>

####VALIDATION

Traditionally this has been a Javascript function but HTML5 are introducing their own which works just as well. This is known a ```<required="required">```

```html
<form action="http://www.example.com/login/" method="post">
  <label for="username">Username:</label>
  <input type="text" name="username" required="required" />
  <label for="password">Password:</label>
  <input type="text" name="password" required="required" />
  <input type="submit" value="Submit" />
</form>
```
<form action="http://www.example.com/login/" method="post">
  <label for="username">Username:</label>
  <input type="text" name="username" required="required" />
  <label for="password">Password:</label>
  <input type="text" name="password" required="required" />
  <input type="submit" value="Submit" />
</form>

####DATE

There is a new easier way to put in Dates, the traditional way involves the text box but in HTML5 they have the ```<input type="date">```

```html
<form action="http://www.example.com/bookings/" method="post">
  <label for="username">Departure Date:</label>
  <input type="date" name="depart" />
  <input type="submit" value="Submit" />
</form>
```
<form action="http://www.example.com/bookings/" method="post">
  <label for="username">Departure Date:</label>
  <input type="date" name="depart" />
  <input type="submit" value="Submit" />
</form>

####EMAIL & URL INPUT

HTML5 has also added an Email element to make things more clear. Browsers that support the new format will check if the user has provided the information (aka, an email address), some will even autofill certain keys such as the '@'

```html
<form action="http://www.example.com/subscribe/">
  <p>Please enter your email here:</p>
  <input type="email" name="email" />
  <input type="submit" value="Submit" />
</form>
```
<form action="http://www.example.com/subscribe/">
  <p>Please enter your email here:</p>
  <input type="email" name="email" />
  <input type="submit" value="Submit" />
</form>

The URL option works the same way, and again browsers will check and/ or help fill in the form:

```html
<form action="http://www.example.com/profile/">
  <p>Please enter your website address here:</p>
  <input type="url" name="website" />
  <input type="submit" value="Submit" />
</form>
```
<form action="http://www.example.com/profile/">
  <p>Please enter your website address here:</p>
  <input type="url" name="website" />
  <input type="submit" value="Submit" />
</form>

####SEARCH

There is also the new ```<input type="search">```

```html
<form action="http://www.example.com/search/">
  <p>Time to begin your search!</p>
  <input type="search" name="search" />
  <input type="submit" value="Search" />
</form>
```
<form action="http://www.example.com/search/">
  <p>Time to begin your search!</p>
  <input type="search" name="search" />
  <input type="submit" value="Search" />
</form>
