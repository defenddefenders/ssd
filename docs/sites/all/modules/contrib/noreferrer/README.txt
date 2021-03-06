NO REFERRER
===========

The rel="noreferrer" attribute[1] indicates that no referrer information is to
be leaked when following the link.

This module adds a rel="noreferrer" attribute to all external links generated by
the theme layer.

It also provides a filter which, if enabled for a text format, adds a
rel="noreferrer" attribute to all external links in user-generated content.

If metatag module[2] is installed, this module also provides a meta referrer
element[3] which can be enabled to set a referrer policy[4] for the page.

[1] https://html.spec.whatwg.org/multipage/semantics.html#link-type-noreferrer
[2] https://drupal.org/project/metatag
[3] https://w3c.github.io/webappsec/specs/referrer-policy/#referrer-policy-delivery-meta
[4] https://w3c.github.io/webappsec/specs/referrer-policy/#referrer-policy-states
