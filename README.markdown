# What is Tinderboost?

If you've compared professional note-taking applications on Mac, you will sooner or later recognize Tinderbox as the most astonishing and powerful [not least because it serves as outliner, mind-mapper, database, GTD assistant and scriptable text exporter and aggregator]. It is also likely that you will grow impatient with its clunky and non-intuitive user interface. 

Tinderbox is immensely powerful, but may lack in eye candy and user friendliness, and most importantly in keyboard shortcuts for productive work. Thanks to Tinderbox very extensive scriptability and the excellent Keyboard Maestro, I have tinkered with the program until it suited my workflow needs. Tinderboost is an extension to make your daily use of Tinderbox more effective, pleasant and to keep those hands on the keyboard. The motivation is to make Tinderbox a bit more similar to [**org-mode**](http://orgmode.org/) -- i.e. a keyboard-focused lightweight notetaker, outliner, reference library and GTD.

> *You may well find your love to Tinderbox rekindled when becoming acquainted with the package.* -- Some Punter

This package provides keyboard automation and interface extensions that allow you to work at the pace of thought:

* Note formatting (colors, size, case)
* Text filtering, quick find/replace
* Quick rule editing
* Quick editing of attributes
* Quick note moving
* Tagging support
* Quick assignment of prototypes
* Note imploding
* Readymade templates to export to PDF and more
* Importing highlights from PDFs

Note:
It's not at all meant to replace the existing user interface altogether. Also, typing prototype names and color name may sound like a way backward when the application allows to click on drop-down lists. If that is how you are using Tinderbox and don't see a reason to change it, please don't bother with this. It won't help you.

# Installation

The package combines the scripting ability of Tinderbox (in the form of "stamps", mostly) with the automation tool Keyboard Maestro[^km_footnote] -- a much recommended addition to any serious Mac user's toolkit.

1. The keyboard activation macros are kept in tinderboost.kmlibrary which can be imported into KMaestro.
2. The Tinderbox stamps are kept in tinderboost.tbx 

# Reference

tinderboost.tbx lists the key bindings for all implemented macros.

[^km_footnote]: Needs version 5 because of its enhanced scripting capacities 

# Contributing

Since both Tinderbox and Keyboard Maestro files are in XML format, it naturally fits in the Git versioning framework.
I know the [Tinderbox community](http://www.eastgate.com/Tinderbox/forum/) is vibrant and I welcome you to adapt it and improve it. 

A lot of help came from the Tinderbox community, in particular the support of Mark Anderson and of [Mark Bernstein](http://markbernstein.org).
