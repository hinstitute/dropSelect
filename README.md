# dropSelect jQuery Plugin

This is a CSS 3/jQuery plugin for making a div based dropdown select box.
All styling is done with CSS. Usage is simple: `$('.mySelectElement').dropSelect()` you're ready to go.
You can then use `$('.mySelectElement').val()` to get the value or use `$('.mySelectElement').val(newValue)` to set the selection to the passed in value (it needs to exist).

Initiation takes an optional object of options:

+ className - Specify the class name to use (defaults to "dropSelect")
+ arrowClass - The class name for the down arrow (defaults to "icon-arrow-down")
+ callBack: A callback function when an item is selected (defaults to null)
+ formatter: A callback to allow user formatting of the inner text (defaults to null)
+ includeEmpties: Set to true to include all empty (no value) items (defaults to false)
+ allowFirstEmptyAsInit: If the first item has no value, include it as initial text (defaults to true)
+ setSelected: When set to true, the selected item in the select box will be matched (defaults to true)
+ forceSelected: If given a value, will make that item selected over anything else (defaults to null)
+ closeOnClick: When set to true, this will close the selection box when an item is clicked (defaults to false)
+ width: The width in your favorite css unit (defaults to "auto", a calculated value based on the longest item length)

Please see the `demo.html` for a full working example.

Checkout our github micro-site (includes the demo): http://tecktron.github.io/dropSelect/

If you run into any problems, please open an issue or feel free to fix it and make a pull request.
