Colpicker
=========

A simple rgba colorpicker as jQuery-plugin. [Demo page](http://pesasa.github.io/colpicker)

Gives a nice ui for selecting color from palette instead of inputing
rgba as hexacode.

License
-------
[MIT-license](http://opensource.org/licenses/MIT)

Usage
-----
Show input field with hex-value and preview area. Preview area is clickable
and clicking shows and hides the palette.

```javascript
jQuery('input#colorbox1').colpicker({
    showInput: true,
    hiddable: true
});
```

Don't show the input field, palette is hidden by default:

```javascript
jQuery('#colorbox2').colpicker({
    showInput: false,
    hiddable: true
});
```

Limit the size of the colorpicker to 400px, show input field, don't hide the
palette.

```javascript
jQuery('#colorbox2').colpicker({
    width: 400,
    showInput: true
});
```
