# Square Chord

Square Chord is an HTML / CSS system for rendering chord charts for songs.
It takes a textual input of chords and renders the result graphically, in a stylized notation where each measure is a square.

## Input notation

The input is plain text broken down into a series of lines, each separated by a newline.

Each line is separated into a series of measures, each separated by a space.

Each measure is separated into a series of beats, each separated by a slash (/).

Each beat or measure can be:

* A chord, represented as text
* Blank, represented by an underscore (_)
* A repeat, represented by a percent sign (%)
