miscellaneous notes on what to work on, things to keep in mind, etc.

to avoid too much painful abstraction, we should expect users to use `_quarto.yml`
- besides the `.qmd` files, what else should we plan on being part of a "normal" experience?

We can put things in folders! So maybe all the "main" content goes in there.
Can't put the index in a folder...
but maybe could do some wacky `include` stuff to *technically*
have a top-level index but not really.

how to use with online RStudio:
- make zip of files (in future we'll provide it)
- upload to a new directory in rstudio
- File::New Project
  + make sure you do "existing project!"
- hit render to render, menu next to it for html/pdf
note on this: not a great way to see the preface/abbreviations...
we should really find a better way to do that
