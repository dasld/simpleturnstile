###############
simpleturnstile
###############

Negated versions and smaller logical turnstiles in LaTeX.

----

This package provides five LaTeX macros that can be used instead of the more
verbose turnstile ones:

* ``\models[A][B]``
    One vertical bar and one horizontal one.
* ``\Models[A][B]``
    One vertical bar and two horizontal ones.
* ``\bimodels[A][B]``
    A horizontally mirrored version of ``\models`` followed by a regular ``\models``.
    They both form a single math relation (a symbol spaced with ``\mathrel``).
* ``\biModels[A][B]``
    A horizontally mirrored version of ``\Models`` followed by a regular ``\Models``.
    They both form a single math relation (a symbol spaced with ``\mathrel``).
* ``\notmodels[A][B]``
   Negated version of ``\models``: a slash crosses the vertical and horizontal bars.
* ``\notModels[A][B]``
   Negated version of ``\Models``: a slash crosses the vertical and horizontal bars.

In all macros, both arguments are optional and rendered as text (not math) in serif font.
``A`` is placed underneath the turnstile, and
``B`` above it.
All macros can be used both in text and math mode.
These turnstiles are all shorter than the ``turnstile`` ones and scale with the font size.

The LaTeX standard ``\models`` macro is still accessible as ``\oldm@dels``.
