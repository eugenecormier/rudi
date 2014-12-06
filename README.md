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
  * diatonic semitones, chromatic semitones & wholetones
  * circle of fifths
  * key signatures
  * scale degrees
  * relative major/minor keys
  * scales
    * major
    * minor
    * chromatic/octatonic/wholetone
    * pentatonic/blues
    * modes
  * intervals
    * easy root simple (bottom note has a key signature)
    * hard root simple (bottom note does not have a key signature)
    * compound (more than an octave)
    * intervals in scales
  * chords (both in root or inversions)
    * major/minor chords
    * diminished/augmented chords
    * dominant 7th chords
    * extended 7th chords
    * clusters, quartal & polychords
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
