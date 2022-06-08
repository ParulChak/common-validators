# common-validators
To use common-validators, just create the instance of validation class and then validator function name
In this repo, till now we have cover

``
  1-Required: requiredValidation();
  ``
  ``
  2-Minlength: minLengthValidation();
  ``
  ``
    3-MaxLength: MaxLengthValidation();
   ``
   ``
     4-Url: urlValidation();
  ``
  ``
  5-Phone: phoneValidation();
  ``
  ``
  6-Custom: customeValidation();
  ``
  ``
  7-regex: regexValidation();
  ``
  
Example:
  const {validators} = require('validation.js')
  const validator = new validator.validation();
  validator.requiredValidation(val); ==> true/false based on value passed
  
