# html-element-fractions
gets element and viewport visibility fractions

this plugin is based on [jQuery.fracs](https://github.com/lrsjng/jquery-fracs/blob/master/src/jquery.fracs.js).

## WARNING

This module is currently with WIP status!!
It isn't ready for production use.

## Installation

```bash
requirehit use html-element-fractions
```

## Usage

Just add this module as a dependency on your `.requirehit.js`, or use provided
installation command to do so.

Then you could use it directly with HTMLElement instances:

```js

    var element = document.createElement( 'div' );
        element.parentNode = document;


    setInterval( function () {
        console.log( element.fracs() );
    }, 1000 );

```
