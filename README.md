### svg-to-stanza

This is built by poet. Please install poet from https://github.com/StanzaOrg/poet

Usage: `svg-to-stanza <name-without-file-extension> [span-in-mm] [stroke-width-in-mm] [ressolution-in-mm]`

If no span, stroke-width or resolution is given, they are default to 10mm, 0.1mm, and 0.01mm respectively.

1. clone this repo
2. use `poet build` to create an executable
3. run the executable against your .svg file. e.g. `svg-to-stanza mirmo`
4. once the .stanza file is generated, you can move it to your jitpcb design directory 
5. use the .stanza file by following the instructions in the .stanza file comments.
6. update your design's `stanza.proj` if necessary.

![alt text](svg-to-stanza-mirmo.png)

Dec 2022
