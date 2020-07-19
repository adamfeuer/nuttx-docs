# The Apache NuttX Documentation (experimental)

This book is meant to be an experiment in replacing the Apache NuttX Documentation with something easier to navigate, extend, and modify.

* You can see the HTML version of this book here: [Apache NuttX Documentation (experimental)](https://nuttx-docs.readthedocs.io).
* You can see the current (original) version of the NuttX Documentation here: 
  [Apache NuttX Documentation](https://cwiki.apache.org/confluence/display/NUTTX/Documentation).

## Building the Documentation

This book is written in [ReStructured Text (RST)](https://docutils.sourceforge.io/rst.html), and built using 
the excellent [Sphinx](https://www.sphinx-doc.org/) documentation system.

To install it, first install Python 3.8 or later and [Pipenv](https://pipenv-fork.readthedocs.io/en/latest/). 
Then do:

```
$ cd nuttx-companion
$ pipenv install
$ pipenv shell
$ cd docs
$ make html

```

The documentation will be in the `_build/html` directory. You can open `_build/html/index.html`.

## Contributing

If there's anything you would like to improve, send me an email or a pull request! See
[Contributing to the NuttX Documentation](https://nuttx-docs.readthedocs.io/en/latest/user/contributing.html) 
for more information.

