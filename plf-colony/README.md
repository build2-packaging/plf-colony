PLF Colony - Build2 Package
===========================

This repository is only setting up the library and it's tests to be published in https://cppget.org through [Build2](http://build2.org).
We use a git submodule targetting a specific version of the library for each package version.

PLF Colony
----------

 - PLF Colony: https://plflib.org/colony.htm
    - Also contain the change history at the end of the page.
 - Repository: https://github.com/mattreecebentley/plf_colony/

## Note about the separate test package:

The separate test package exists because the tests of `plf-colony v6.x` depended on `plf-rand` so to avoid additional dependencies for people wanting to use `plf-colony` without the tests we split it in 2 packages, the test one being the one depending on `plf-rand`, while `plf-colony` does not.
However tests in versions `7.x` of `plf-colony` do NOT have any dependencies, which makes the separated test package more complicated than necessary as the tests could be part of the `plf-colony` package.
However, to avoid complicated changes in this repository and to allow easilly re-enabling dependencies in tests in the future, we will keep the separate packages as before.


Package Maintainers
-------------------

- A. Joël Lamotte - mjklaim@gmail.com