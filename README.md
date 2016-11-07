# date-input-mask

A date input mask. Limits data entry to DD/DD/DDDD where D is a digit (0-9).

## Installation 

Browserify:

    npm install --save @nib-components/date-input-mask
    
## Usage

HTML:

    <input/>

JavaScript:

    var mask  = require('@nib-components/date-input-mask');
    var el    = document.querySelector('input');
    
    mask(el);
    
## Change Log

### `1.0.0`

- Drop support for component