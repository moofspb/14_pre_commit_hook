# Quadratic Equations Solver

The module quadratic_equation.py includes function get_roots
 that takes args a, b, c and returns roots of quadratic equation.

The arguments a, b, and c are the coefficients of the equation.

# Pre-commit hook

If you want to use pre-commit hook paste `pre-commit` file in
 `.git/hooks` directory and mark it as executable using chmod:

`chmod +x pre-commit`

After that tests will be run automatically when you try to commit.
 If tests fail commit will be aborted.

# Usage

```#!bash

from quadratic_equation import get_roots
roots = get_roots(1, 3, -4)
roots
(-4.0, 1.0)
```

# Tests

Also, there is module tests.py that contains unit tests. You can run it by typing:

```#!bash

$ python tests.py
```
