colourfill
==========
Colourfill is a jQuery colouring plugin that allows you to "colour in" elements based on your screen specified "choose a color" buttons. It is adapted from code I created to help build an online colouring book website - <a href="http://colourfill.ca">colourfill.ca</a>.

Author
-------
<a href="http://audrianaandrews.com" target="_blank">Audriana Andrews</a>

Example Use
---------
```javascript
$("#container").colourfill({
        buttons: ".button",
        colourableElements:".box",
        undoButton: ".undo",
        resetButton: ".reset"
 });
```

Default Options
---------------
```javascript
$([container]).colourfill({
        buttons: null,
        colourableElements: null,
        undoButton: null,
        resetButton: null, 
        fillType: "background-color", 
        buttonColourType: "background-color", 
        addColouredClass: "false" 
 });
```

All Options
-----------
**buttons, colourableElements, undoButton, resetButton**<br>
Add the selectors you used to create these. The colour that is currently active has the class "colourChosen".

**fillType, buttonColourType: {'background-color', 'fill'}**<br>
Choose what CSS property the colours for the "choose a colour" buttons and the colourable elements you want to fill in come from.

**addColouredClass: {'true', 'false'}**<br>
Add the class "coloured" to an element after it is coloured in.

Example
--------
<a href="http://audrianaandrews.com/portfolio/colourfill-plugin-test" target="_blank">Click here to see a working example of the plugin.</a>

License
-------
This plugin is licensed under the MIT License - see the included LICENSE file for details.
