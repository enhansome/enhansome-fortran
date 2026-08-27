# Awesome Fortran with stars

A curated list of awesome Fortran frameworks, libraries and software. Inspired by [awesome-swift](https://github.com/Wolg/awesome-swift) ⭐ 5,883 | 🐛 111 | 📅 2026-04-12 by @Wolg.

* [Awesome Fortran](#awesome-fortran)
  * [Functional Libraries](#functional-libraries)
  * [Graphics Libraries](#graphics-libraries)
  * [Math libs](#math-libs)
  * [JSON Manipulation](#json-manipulation)
  * [XML Manipulation](#xml-manipulation)
  * [Date and time manipulation](#date-and-time-manipulation)
  * [Testing](#testing)
  * [Encoding-Decoding](#encoding-decoding)
  * [Portability enabling](#portability-enabling)
  * [Command-Line parsing](#command-line-parsing)
  * [Compiling and building](#compiling-and-building)
  * [Preprocessor](#preprocessor)
  * [Formatting](#formatting)
  * [Automatic documentation](#automatic-documentation)
  * [Computational Fluid Dynamics](#computational-fluid-dynamics)
  * [Docker](#docker)
  * [Web](#web)
* [Resources](#resources)
  * [Fortran Websites](#fortran-websites)
    * [Fortran Videos](#fortran-videos)
* [Other Awesome Lists](#other-awesome-lists)
* [Contributing](#contributing)

## Functional Libraries

* [Functional Fortran](https://github.com/wavebitscientific/functional-fortran) ⭐ 437 | 🐛 4 | 🌐 Fortran | 📅 2023-02-13 - Functional programming for modern Fortran.

## Graphics Libraries

*Libraries for graphing, graphics, and GUIs*

* [gtk-fortran](https://github.com/vmagnin/gtk-fortran/wiki) ⭐ 289 | 🐛 13 | 🌐 Fortran | 📅 2026-07-15 - a cross-platform library to build Graphical User Interfaces (GUI) using [GTK+](https://www.gtk.org/).  Very useful when combined with the [Glade](https://glade.gnome.org/) RAD tool.
* [VTKFortran](https://github.com/szaghi/VTKFortran) ⭐ 156 | 🐛 19 | 🌐 Fortran | 📅 2026-07-01 - Pure Fortran (2003+) library to write and read data conforming the VTK standard.
* [DISLIN](https://www.mps.mpg.de/dislin/) - a high-level graphing and user-interface library.
* [f90gl](https://math.nist.gov/f90gl/) - public domain implementation of the official NIST Fortran 90 bindings for OpenGL.
* [F03GL](http://www-stone.ch.cam.ac.uk/pub/f03gl/index.xhtml) - a Fortran 2003 interface to the OpenGL library, along with the GLU and GLUT toolkits.
* [PGPLOT](https://www.astro.caltech.edu/~tjp/pgplot/) - cross-platform scientific graphing library.

## Math Libs

*Libraries for calculating and other mathematical operations.*

* [OpenBLAS](https://github.com/xianyi/OpenBLAS) ⭐ 7,563 | 🐛 116 | 🌐 C | 📅 2026-08-26 - one of the fastest open source BLAS libraries available.  Almost as fast as Intel MKL.
* [netCDF](https://github.com/Unidata/netcdf-fortran) ⭐ 270 | 🐛 124 | 🌐 Fortran | 📅 2026-07-29 - a set of software libraries and self-describing, machine-independent data formats that support the creation, access, and sharing of array-oriented scientific data.
* [BLAS](http://www.netlib.org/blas/) - application programming interface standard for publishing libraries to perform basic linear algebra operations such as vector and matrix multiplication.
* [CERNLIB](http://cernlib.web.cern.ch/cernlib/) - The CERN Program Library is a large collection of general purpose libraries and modules maintained and offered in both source and object code form on the CERN central computers
* [EISPACK](http://www.netlib.org/eispack/) - a software library for numerical computation of eigenvalues and eigenvectors of matrices, written in FORTRAN
* [FGSL](https://www.lrz.de/services/software/mathematik/gsl/fortran/index.html) - portable, object-based Fortran interface to the [GNU scientific library](https://www.lrz.de/services/software/mathematik/gsl/)
* [IMSL](https://www.imsl.com/products/imsl-fortran-libraries) - The IMSL Fortran Numerical Library is the standard for high performance computing commercial mathematics and statistics libraries
* [Lis](https://www.ssisc.org/lis/index.en.html) - a Library of Iterative Solvers for Linear Systems
* [NAG Fortran Library](https://www.nag.co.uk/content/nag-library-fortran) - Produced by experts for use in a variety of applications, the NAG Fortran Library has a global reputation for its excellence and, with hundreds of fully documented and tested routines, is the largest collection of mathematical and statistical algorithms available

## JSON Manipulation

*Libraries for JSON data manipulating with Fortran language.*

* [json-fortran](https://github.com/jacobwilliams/json-fortran) ⭐ 381 | 🐛 25 | 🌐 Fortran | 📅 2026-06-11 - A Fortran 2008 JSON API.
* [FSON](https://github.com/josephalevin/fson) ⭐ 61 | 🐛 11 | 🌐 Fortran | 📅 2023-01-23 - Fortran 95 JSON Parser.

## XML Manipulation

*Libraries for XML data manipulating with Fortran language.*

* [fox](https://github.com/andreww/fox) ⭐ 65 | 🐛 36 | 🌐 Fortran | 📅 2022-02-08 - Fortran XML library
* [xml-fortran](https://sourceforge.net/projects/xml-fortran/) - an all-Fortran solution for reading and writing XML files.

## Date and time manipulation

*Libraries for date and time manipulation with Fortran language.*

* [datetime-fortran](https://github.com/wavebitscientific/datetime-fortran) ⭐ 151 | 🐛 11 | 🌐 Fortran | 📅 2023-06-20 - A Fortran 2003 date and time manipulation library, modeled after Python's datetime library.

## Testing

*Libraries for testing codebases and generating test data.*

* [FRUIT](https://sourceforge.net/projects/fortranxunit/) - FORTRAN Unit Test Framework, written in FORTRAN 95
* [Ftunit](http://flibs.sourceforge.net/ftnunit.html) - Fortran unit testing framework by Arjen Markus
* [pFUnit](https://sourceforge.net/projects/pfunit/) - Unit testing framework for Fortran with MPI extensions by developers from NASA and NGC TASC.  Uses parallel codes and object-oriented design.
* [Vegetables](https://gitlab.com/everythingfunctional/vegetables) - For a healthier code base, eat your vegetables

## Encoding-Decoding

*Libraries for encoding and decoding data with Fortran language.*

* [BeFoR64](https://github.com/szaghi/BeFoR64) ⭐ 22 | 🐛 1 | 🌐 Fortran | 📅 2026-07-01 - Base64 encoding/decoding library for FoRtran poor men. A KISS library for base64 encoding/decoding for modern (2003+) Fortran projects.

## Portability enabling

*Libraries for enabling codes portability.*

* [PENF](https://github.com/szaghi/PENF) ⭐ 42 | 🐛 3 | 🌐 Fortran | 📅 2026-07-01 - Pure Fortran (2003+) library for ensuring codes portability.

## Command-Line parsing

*Libraries for parsing command-line and building user interfaces.*

* [FLAP](https://github.com/szaghi/FLAP) ⭐ 171 | 🐛 21 | 🌐 Fortran | 📅 2026-07-01 - Fortran command Line Arguments Parser for poor men. A KISS library for building easily nice Command Line Interfaces (CLI) for modern (2003+) Fortran projects.
* [options.f90](https://github.com/cngilbreth/optionsf90) ⭐ 12 | 🐛 2 | 🌐 FORTRAN | 📅 2015-03-22 - Options & input processing for modern Fortran.

## Compiling and building

*Libraries for compiling and building Fortran projects.*

* [FoBiS](https://github.com/szaghi/FoBiS) ⭐ 144 | 🐛 5 | 🌐 Python | 📅 2026-08-09 - Fortran Building System for poor men. A KISS tool for automatic building modern Fortran projects.

## Preprocessor

*Libraries for conditional-compilation, macros for code simplification, and inclusion of additional source files, templating systems.*

* [PreForM](https://github.com/szaghi/PreForM) ⭐ 23 | 🐛 7 | 🌐 Python | 📅 2020-10-08 - Preprocessor for Fortran poor Men.
* [Blockit/PyF95++](http://blockit.sourceforge.net/) - A fairly simple Python framework used to block parse your code (or any text file) into nested blocks. The BlockIt framework has already been used to create a templating capability for the Fortran 95/2003 language along with some language extensions.

## Formatting

*Tools for formatting and style-checking Fortran source code.*

* [ffmt](https://github.com/sbryngelson/ffmt) ⭐ 6 | 🐛 1 | 🌐 Rust | 📅 2026-07-14 - Fast, configurable Fortran formatter with support for Fypp, Doxygen, and OpenACC/OpenMP directives. Written in Rust, installable via pip.

## Automatic documentation

*Libraries for building documentation.*

* [FORD](https://github.com/cmacmackin/ford) ⭐ 40 | 🐛 0 | 🌐 Python | 📅 2020-12-28 - An automatic documentation generator for modern Fortran programs.

## Computational Fluid Dynamics

*Libraries for CFD computations*

* [MFC](https://github.com/MFlowCode/MFC) ⭐ 412 | 🐛 110 | 🌐 Fortran | 📅 2026-08-27 - Exascale multiphase compressible flow solver with GPU acceleration via OpenACC. 2025 Gordon Bell Prize Finalist.
* [OFF](https://github.com/szaghi/OFF/tree/testing) ⭐ 150 | 🐛 5 | 🌐 Fortran | 📅 2019-11-08 - Open source Finite volume Fluid dynamics code.

## Docker

* [Unoficial Image](https://hub.docker.com/r/baekjoon/onlinejudge-fortran/) - docker image provided by @baekjoon

## Web

* [Fortran Machine](https://github.com/mapmeld/fortran-machine) ⭐ 811 | 🐛 2 | 🌐 Fortran | 📅 2021-09-14 - An MVC web stack written in Fortran 90

# Resources

Various resources, such as books, websites and articles, for improving your Fortran development skills and knowledge.

## Fortran Websites

* [The Fortran Company](https://www.fortran.com/) - A home page of FORTRAN programming language.
* [Fortran Dev](https://fortrandev.wordpress.com/) - Fortran development blog.
* [Fortran WIKI](http://fortranwiki.org/fortran/show/HomePage) - An open venue for discussing all aspects of the Fortran programming language and scientific computing.

## Fortran Videos

* [GNU FORTRAN Lesson 1](https://www.youtube.com/watch?v=qUy8M10uZRU) - Videos about the Fortran programming language.

# Other Awesome Lists

Other amazingly awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) ⭐ 33,632 | 🐛 62 | 🌐 Ruby | 📅 2024-06-02 list.

# Contributing

Your contributions are always welcome! Please submit a pull request or create an issue to add a new framework, library or software to the list. Do not submit a project, which hasn't been updated in the past 6 months or is not awesome.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-27._
