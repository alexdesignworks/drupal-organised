# JavaScript

* Files **MUST** be stored in module's `js` directory.
* JS files **MUST** be named as a module name with underscored replaced by

  dashes. E.g, `my_module` =&gt; `my­-module.js`.

* More specific JS files **SHOULD** be included separately and named

  with `.my-feature` suffix. I.e. `my-module.my-feature.js`.

* Use the following template as a scaffolding code:

```javascript
/**
 * @file
 *
 */

/*global jQuery, Drupal*/

(function ($) {
  'use strict';
  Drupal.behaviors.my_module = {
    attach: function (context) {

    }
  };
}(jQuery));
```

