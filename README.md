# HMS Field

HMS Field displays an integer formatted as Hours, Minutes or Seconds.
The field stores values as integer. Both input and output can be formatted as
Hours, Minutes and/or Seconds. Alter functions provide a way for developers to
add their own format.

### Formats
Pick one of these formats for input or output:

* h:mm
* h:mm:ss
* m:ss
* h
* m
* s

Or alternatively, use hook_hms_format_alter() to add/edit your own format.

Detail in READMEs should be limited to the minimum required for installation and
getting started. More detailed documentation should be moved to a GitHub wiki
page: https://github.com/backdrop-contrib/setup/wiki/Documentation.

Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules.

- Add a field to an entity and select "Hours Minutes and Seconds" as field type.

Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/hms_field/issues.

Current Maintainers
-------------------

- [argiepiano](https://github.com/argiepiano).

Credits
-------

- Ported to Backdrop CMS by [argiepiano](https://github.com/argiepiano).
- Originally written for Drupal by [Drupal internetbureau .VDMi/ in Rotterdam, The Netherlands.](https://vdmi.nl/).
- Based on the [MagicalCode project](https://github.com/example).
- Sponsored by [TechNoCorp](https://example.com)

License
-------

This project is GPL v2 software. 
See the LICENSE.txt file in this directory for complete text.
