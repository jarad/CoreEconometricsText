A free graduate Econometrics textbook
=====================================

The goal of this project is to produce and maintain as a community a
free textbook/research monograph on Econometrics suitable for teaching
a PhD core course and make it available through the
[GNU Free Documentation License](http://www.gnu.org/copyleft/fdl.html).

The project is just getting started. Use at your own risk!

Material covered
----------------

* Probability (see probability.tex for a list of sections)
* Finite-sample statistics (finitesample.tex)
  * Point estimation
  * Hypothesis testing
  * Bayesian inference
* Asymptotics (asymptotics.tex)
* Linear regression (linearregression.tex)

License
-------

Copyright © 2013, authors of the "Econometrics Core" textbook; a
complete list of authors is available in the file AUTHORS.tex.

Permission is granted to copy, distribute and/or modify this document
under the terms of the GNU Free Documentation License, Version 1.3 or
any later version published by the Free Software Foundation; with no
Invariant Sections, no Front-Cover Texts, and no Back-Cover Texts.  A
copy of the license is included in the file LICENSE.tex and is also
available online at <http://www.gnu.org/copyleft/fdl.html>.

### Additional files available under different licenses

The LaTeX class this project uses was developed by the Tufte-LaTeX
project under the Apache 2.0 license, available at
<http://www.apache.org/licenses/LICENSE-2.0>, and the Copyright is
held by Kevin Godby, Bil Kleb, and Bill Wood.  The Apache 2.0 license
applies to the files:

* `tex/tufte.bst`
* `tex/tufte-book.cls`
* `tex/tufte-common.def`
* `tex/tufte-handout.cls`

Development Notes
-----------------

* To generate pdfs, run the command `make` in the top-level directory
  of this project (you'll need to have `make` installed, obviously).

* Type `make ver` to update the date and version information included
  in each pdf file.

* Please email the mailing list (see below) if you run into problems
  or have any other questions.

More information
----------------

There are two "best" ways of contacting us.  The first is through the
mailing list for the [Econometrics Free
Library](http://www.econometricslibrary.org),
<econometricslibrary@librelist.com> (this is the mailing list for our
parent project); the [Librelist homepage](http://librelist.com/) has
more information about sending messages to this discussion list and
[archives are available online as
well](http://librelist.com/browser/econometricslibrary/).  The second
is by [filing an issue report for the
project](https://github.com/EconometricsLibrary/GraduateText/issues/new).

If you find an error in the text, please let us know through one of
those methods.  If you'd like to contribute to this project, please
subscribe to the mailing list.

You can also follow dedicated RSS feeds that announce new commits to
the project's GitHub repositories:
* [the master branch](https://github.com/EconometricsLibrary/CoreEconometricsText/commits/master.atom)
* [the development branch](https://github.com/EconometricsLibrary/CoreEconometricsText/commits/dev.atom)
