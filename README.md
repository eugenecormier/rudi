rudi
====

A randomized music theory rudiments worksheet/test and key generator

The purpose of this program's existance is so that
Eugene can run a command and have a random theory
test/worksheet and key created using lilypond as a backend.

modules:
  * aural intervals (just fill in boxes)
  * clefs
  * note names
  * durations
  * dst, cst, wt
  * circle of fifths
  * key signatures
  * scale degrees
  * relative major/minor
  * scales
    * major
    * minor
    * chromatic/octatonic/wholetone
    * pentatonic/blues
    * modes
  * intervals
  * chords
  * cadences
  * transposing
  * time signatures
  * detect errors

We then call the program with parameters like:
rudi --scales-majmin
or:
rudi --scales-majmin 20
or:
rudi --draw-clefs 15 --scales-majmin
or:
rudi --all

Dependancies:
 * Python 3
 * Lilypond 2.18 (it may run on newer versions
    but this has not been tested. I'll update it
    for future versions as they become stable in
    Gentoo.
 * Copy the cof.eps into the folder /usr/share/rudi/

The License is GPL V2
