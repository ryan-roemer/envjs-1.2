===========
 Envjs 1.2
===========
:Info: Envjs 1.2 patched for jQuery 1.5+.
:Author: Ryan Roemer (http://github.com/ryan-roemer)

Patched version of `Envjs 1.2`_ with some basic bug fixes and attribute
additions for compatibility with jQuery 1.5+.

Patches:

* Missing ``__trim__`` function definition added to closure.
* Add toLowerCase() for cookie names.
* Additional attributes for jQuery 1.5+: ``clearAttributes``,
  ``mergeAttributes``, ``get value``, ``set value``. Backported from
  orslumen_'s patches for Envjs 1.3.

.. _`Envjs 1.2`: http://www.envjs.com/dist/env.rhino.1.2.js
.. _orslumen: https://github.com/orslumen/env-js/commit/
    c3e702cfa84872782dd40a2c4cd8a4c8f9bac3a3
