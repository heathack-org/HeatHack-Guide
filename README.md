# HeatHack Guide Book

Materials for running the group sessions of HeatHack's structured programme for groups to think about how to reduce energy use and what net zero means for their traditionally-built community buildings.  The Guide Book replaces 
jeancarletta's HeatHack-Sessions repository.

Written in Jupyter Book.

To test a local build, in a python environment with jupter-book installed,

jupyter-book build . --builder html --all

## Card game section

This is largely generated from a spreadsheet, using hand-authored pages to introduce the game, describe the wildcard, and describe excluded actions. There is a wildcard row in the spreadsheet (card 48) and the hand-authored version is just a doctored copy.


There is some hand-authored content for some of the cards in the card-explanations directory; this is appended to the automatically generated content. The explanations are now just links into other parts of the guide book so that we can shift them into the spreadsheet, making it easier to manage them.

To generate the table of contents and most of the website pages:

Create a virtual python environment and install openpyxl and pandas; activate it.


python -m venv card-game-venv   --- to create virtual environment
source card-game-venv/bin/activate --- to start using the virtual environment
python -m pip install openpyxl pandas

Cd to the aux directory.  Ensure master-spreadsheet.xlsx contains the spreadsheet source.  It needs a steps and a cards worksheet and columns as names in cards-template.txt and steps-template.txt.

python generate-website.py

The output will appear in the output subdirectory - _toc_cards.yml, and _steps and _cards subdirectories containing markdown files.  Replace _steps and _card in the card-game directory with these items and stick the _toc_cards.yml contents in the right place in _toc.yml items in the top level directory with the new versions.

## Intended workflow

Intended workflow (Simplified GitFlow with developers working on one branch):

          dev         - author materials here; there isn't much chance we'll conflict but push often
           |
           |
           |
          main        -  when materials are ready to build into website, copy that part into main (see below).
           |
           |
           |
        gh-pages      - complete derivative branch produced automatically, do not edit; contains website
