# Player Behaviour Tracking Paper Collection

This repository contains code for generating a static HTML page using fields from a .bib file.

It specifically focusses on player behaviour tracking research, which concerns the computation of behavioural measures for collection of players using their gambling transaction data.

### `.bib` fields
To use this project effectively, your .bib file should be in proper BibTeX format, plus a field called `measures` containing a comma seperated list of names of behavioural measures.
Each of these behavioural measures can optionally hold a description which can be delimited using a colon as follows;

`measures = {name: this is a measure, another: this is another measure}`

