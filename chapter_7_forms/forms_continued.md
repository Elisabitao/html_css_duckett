###CONTROLS (Types of input!)
####TEXT

The ```<input>``` element is used to create several different form controls. For eg: ```type="text"``` - which means single line input. The server needs to know which form control the user entered data into, therefore the *name* needs to be clarified. *Size* attribute should __NOT__ be used in new forms any more, though just as a reminder, they were measured in character length. Oddly though, the```maxlength="8"``` attribute is fine to still use....

```html
<form action="http://www.example.com/subscribe.php">
  <p>Username:
    <input type="text" name="username" size="15" size="20" maxlength="25" />
  </p>
  <p>Password:
    <input type="password" name="password" size="20" maxlength="15">
  </p>
</form>
```
<form action="http://www.example.com/subscribe.php">
  <p>Username:
    <input type="text" name="username" size="15" size="20" maxlength="25" />
  </p>
  <p>Password:
    <input type="password" name="password" size="20" maxlength="15">
  </p>
</form>

As you can see the Password attribute is the same as the single-line text element, EXCEPT that it blocks out the text input for obvious security reasons.

Textarea element is used to create multiline text input and thus the number of rows and columns USE TO be an important part of it but again, ideally this should be done in CSS instead.
```html
<form action="http://www.example.com/subscribe.php">
  <p>What do you think of your revision period so far?</p>
  <textarea name="" id="" cols="30" rows="10">Enter your user experience here:</textarea>
</form>
```
<form action="http://www.example.com/subscribe.php">
  <p>What do you think of your revision period so far?</p>
  <textarea name="" id="" cols="30" rows="10">Enter your user experience here:</textarea>
</form>

####RADIO & CHECKBOX BUTTONS

Radio buttons are 'multiple choice' option buttons, just make sure the *name* is consistent with all the buttons themselves aka, an umbrella title. The *value* is what we see the button called on the screen.

  * Radio buttons do not allow users to deselect!!! Thay HAVE TO choose something else instead once they have made any choice!!! If you want to be able to DESELECT then use a __CHECKBOX__ button instead!!!

```html
<form action="http://www.example.com/subscribe.php">
  <p>Which is your favourite element to bend?
  <br />
    <input type="radio" name="elements" value="earth" checked="checked" />Earth
    <input type="radio" name="elements" value="air" />Air
    <input type="radio" name="elements" value="fire" />Fire
    <input type="radio" name="elements" value="water" />Water
  </p>
</form>
```
<form action="http://www.example.com/subscribe.php">
  <p>Which is your favourite element to bend?
  <br />
    <input type="radio" name="elements" value="earth" />Earth
    <input type="radio" name="elements" value="air" />Air
    <input type="radio" name="elements" value="fire" />Fire
    <input type="radio" name="elements" value="water" />Water
  </p>
</form>

####DROP DOWN  & MULTIPLE SELECT MENUS

The main difference here is that there is a ```<select></select>``` element, which contains at least 2 options. 'Name' and 'value' have the same jobs, while the ```<option></option>``` tag is used to give us options to choose from, surprise surprise...They are more similar with radio buttons than checkboxes as far as unchecking is concerned.

```html
<form action="http://www.example.com/subscribe.php">
  <p>What attribute is associated with the Fire nations?</p>
    <select name="national traits">
      <option value="cmmunity">Community</option>
      <option value="endurance">Endurance</option>
      <option value="will power">Will power</option>
      <option value="pacifist">Pacifist</option>
    </select>
</form>
```
<form action="http://www.example.com/subscribe.php">
  <p>What attribute is associated with the Fire nations?</p>
    <select name="national traits">
      <option value="cmmunity">Community</option>
      <option value="endurance">Endurance</option>
      <option value="will power">Will power</option>
      <option value="pacifist">Pacifist</option>
    </select>
</form>

multiple select boxes are the exact same as above, except they include the ```size=""``` attribute so you can see all the options at once, and if you wanted to allow the users to select multiple options then you simply add in the ```multiple="multiple"``` attribute too (though they must hold down the cmd OR ctl key at the same time):

```html
<form action="http://www.example.com/subscribe.php">
  <p>What attribute is associated with the Fire nations?</p>
    <select name="national traits" size="4" multiple="multiple">
      <option value="cmmunity">Community</option>
      <option value="endurance">Endurance</option>
      <option value="will power">Will power</option>
      <option value="pacifist">Pacifist</option>
    </select>
</form>
```
<form action="http://www.example.com/subscribe.php">
  <p>What attribute is associated with the Fire nations?</p>
    <select name="national traits" size="4" multiple="multiple">
      <option value="cmmunity">Community</option>
      <option value="endurance">Endurance</option>
      <option value="will power">Will power</option>
      <option value="pacifist">Pacifist</option>
    </select>
</form>

####SUBMIT BUTTON

This goes back to the ```<input>``` tag and means that the type is now:```<type="submit">```. Now the ```Name``` becomes the point of the button or its purpose aka, *if you submit a invoice then you can name it that*. The ```value``` is now *whats written on the button* or seen by the user.
```html
<form action="http://www.example.com/subscribe.php">
  <p>Subscribe to some shitty email list:</p>
  <input type="text" name="email"><!-- this is the text box to put your email into -->
  <input type="submit" name="Subscribe"><!--  this is the button -->
</form>
```
<form action="http://www.example.com/subscribe.php">
  <p>Subscribe to some bloody email list:</p>
  <input type="text" name="email">
  <input type="submit" name="Subscribe">
</form>
