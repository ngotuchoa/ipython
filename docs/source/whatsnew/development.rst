=====================
 Development version
=====================

This document describes in-flight development work.

.. warning::

    Please do not edit this file by hand (doing so will likely cause merge
    conflicts for other Pull Requests). Instead, create a new file in the
    `docs/source/whatsnew/pr` folder


- `%%capture` cell magic now captures the rich display output, not just
  stdout/stderr


Backwards incompatible changes
------------------------------

* Python 2.6 and 3.2 are no longer supported: the minimum required
  Python versions are now 2.7 and 3.3.
* The Transformer classes have been renamed to Preprocessor in nbconvert and
  their `call` methods for them have been renamed to `preprocess`.
* The `call` methods of nbconvert post-processsors have been renamed to
  `postprocess`.
