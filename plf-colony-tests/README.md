# plf-colony-tests

Tests for the `plf-colony` package.

### Note

This package exists because the tests of `plf-colony v6.x` depended on `plf-rand` so to avoid additional dependencies for people wanting to use `plf-colony` without the tests we split it in 2 packages, the present one being the one with the tests and depending on `plf-rand`.
Versions `7.x` of `plf-colony` do NOT have any dependencies however, which makes this package more complicated than necessar as the tests can be part of the `plf-colony` package.
However, to avoid complicated changes in this repository and to allow easilly re-enabling dependencies in tests in the future, we will keep the separate packages as here for now.

