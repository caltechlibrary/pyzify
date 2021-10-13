# Pyzify<img width="12%" align="right" src="https://github.com/caltechlibrary/pyzify/raw/main/.graphics/pyzify-icon.png">

A small program to create self-contained executable Python ["zipapps"](https://docs.python.org/3/library/zipapp.html) using [shiv](https://github.com/linkedin/shiv).

[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg?style=flat-square)](https://choosealicense.com/licenses/bsd-3-clause)
[![Latest release](https://img.shields.io/github/v/release/caltechlibrary/pyzify.svg?style=flat-square&color=b44e88)](https://github.com/caltechlibrary/pyzify/releases)


## Table of contents

* [Introduction](#introduction)
* [Installation](#installation)
* [Usage](#usage)
* [Known issues and limitations](#known-issues-and-limitations)
* [Getting help](#getting-help)
* [Contributing](#contributing)
* [License](#license)
* [Authors and history](#authors-and-history)
* [Acknowledgments](#authors-and-acknowledgments)


## Introduction

Pyzify is a small program that does two things:

1. Creates a self-contained and executable Python [zipapp](https://docs.python.org/3/library/zipapp.html) from your Python source code. The resulting binary contains a bootstrap component and a [pyz](https://www.python.org/dev/peps/pep-0441/) bundle of your application files with all the Python dependencies included. To run, the application **only needs a Python interpreter of the right version on users' computers** &ndash; users don't need to install other Python packages themselves because the binary contains everything it needs. It's almost like a regular compiled program!
2. Bundles the executable application into a zip archive suitable for distribution. The zip archive contains a README file with information about the application; the README is constructed using a pyzify that you supply, letting you customize its contents.

Pyzify is uses [shiv](https://github.com/linkedin/shiv) to do the real work. It adds some bootstrap code to test the version of Python at run-time and additional steps to create the zip archive for distribution.


## Installation


## Usage


## Known issues and limitations


## Getting help

If you find an issue, please submit it in [the GitHub issue tracker](https://github.com/caltechlibrary/pyzify/issues) for this repository.


## Contributing

I would be happy to receive your help and participation with enhancing Handprint!  Please visit the [guidelines for contributing](CONTRIBUTING.md) for some tips on getting started.


## License

Software produced by the Caltech Library is Copyright © 2021 California Institute of Technology.  This software is freely distributed under a BSD/MIT type license.  Please see the [LICENSE](LICENSE) file for more information.


## Authors and history

Pyzify started as a script used by the author to create self-contained applications for [Handprint](https://github.com/caltechlibrary/handprint) and [eprints2bags](https://github.com/caltechlibrary/eprints2bags). It was spun out as its own project late in the year 2021.


## Acknowledgments

This work was funded by the California Institute of Technology Library.

The [vector artwork](https://thenounproject.com/search/?q=package&i=3467951) used as a starting point for the logo for this repository was created by [Komkrit Noenpoempisut](https://thenounproject.com/itim2101/) for the [Noun Project](https://thenounproject.com).  It is licensed under the Creative Commons [Attribution 3.0 Unported](https://creativecommons.org/licenses/by/3.0/deed.en) license.  The vector graphics was modified by Mike Hucka to change the color.

<div align="center">
  <br>
  <a href="https://www.caltech.edu">
    <img width="100" height="100" src="https://raw.githubusercontent.com/caltechlibrary/pyzify/main/.graphics/caltech-round.png">
  </a>
</div>
