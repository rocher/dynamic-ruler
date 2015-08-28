[![License GPL 3](http://img.shields.io/badge/license-GPL3-red.svg)](http://www.gnu.org/licenses/gpl-3.0.txt)
[![MELPA Stable](http://stable.melpa.org/packages/dynamic-ruler-badge.svg)](http://stable.melpa.org/#/dynamic-ruler)
[![issues](http://img.shields.io/github/issues/rocher/dynamic-ruler.svg)](https://github.com/rocher/dynamic-ruler/issues)

## dynamic-ruler for Emacs ##

This is an Emacs package to show a dynamic ruler that can be freely
moved around the buffer, for measuring and positioning text.

![screenshot](https://raw.githubusercontent.com/rocher/dynamic-ruler/master/dynamic-ruler.gif)

## Installation ##

### Manual ###

Download
[dynamic-ruler.el](https://raw.githubusercontent.com/rocher/dynamic-ruler/master/dynamic-ruler.el)
to your emacs library and add this line to your `.emacs` file:

```lisp
(require 'dynamic-ruler)
```

### Package.el ###

Dynamic ruler is available in [MELPA](http://melpa.org). You can
install it with:

`M-x install-package dynammic-ruler`


## Bugs & Improvements ##

Please report any problems that you find on the
[project issue tracker](https://github.com/rocher/dynamic-ruler/issues). If
you've added some improvements and you want them included upstream
don't hesitate to send me a patch or even better - a GitHub pull
request.

<img style="border:solid 1px #ccc" src="https://raw.githubusercontent.com/rocher/dynamic-ruler/master/dynamic-ruler-vertical.gif" />

## Copyright and License ##

Copyright (C) 2015 Francesc Rocher francesc.rocher@gmail.com

Licensed under the GNU GPL version 3 or later, see LICENSE for more
information.

### Note ###

> This ruler is based on the `popup-ruler` by Rick Bielawski, which in
> turn was *inspired by the one in fortran-mode but code-wise bears*
> *no resemblance*.


[![Support via Gratipay](https://cdn.rawgit.com/gratipay/gratipay-badge/2.3.0/dist/gratipay.png)](https://gratipay.com/rocher/)
