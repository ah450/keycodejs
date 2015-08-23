KeyKodesjs
============
Lookup tables and comparison functions for keycodes, enough with the magic numbers!

Namespacing by type. 
Declares a global variable `keyKodes`


#Install
`bower install keykodesjs --save`

#Usage

```javascript
  $('blahblah').keydown( function(event) {
    if (event.which == keyKodes.arrows.up) {
      // do something
    }
  });
```