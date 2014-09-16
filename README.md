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
  ranthetest --scales-majmin
or:
  ranthetest --scales-majmin 20
or:
  ranthetest --draw-clefs 15 --scales-majmin
or:
  ranthetest --all

To Do:
  compound intervals
  double check TranspositionInstrumentsDict
  after complete, remove tmp lilypond files

Dependancies:
 * Python 3
 * Lilypond 2.16.2 (it may run on newer versions
    but this has not been tested. I'll update it
    for future versions as they become stable in
    Gentoo.
 * Copy the cof.eps into the folder .rudi/

Eugene Cormier March 11, 2014
