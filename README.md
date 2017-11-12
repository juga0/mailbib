
Overview
--------
This repository contains the BibTeX file and HTML templates that are used to
create the Mix Network Bibliography, mailbib.

Build it
--------

You first need [`bibliogra.py`](https://github.com/NullHypothesis/bibliograpy)
to turn the BibTeX file into an HTML bibliography. For convenience there is
a copy in this repo.

Then, run the following commands to write the bibliography to `OUTPUT_DIR`.

    $ ./fetch_pdfs.py references.bib OUTPUT_DIR
    $ bibliogra.py -H header.tpl -F footer.tpl -f references.bib OUTPUT_DIR


Acknowledgements
----------------
Shamelessly copied from https://github.com/applied-mixnetworks/mailbib

Thanks to Philipp Winter, this repository is inspired by the censorbib repo:

https://github.com/NullHypothesis/censorbib
