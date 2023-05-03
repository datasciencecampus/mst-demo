# MST Demonstration

This directory contains the materials needed to demonstrate the MST method for
synthesising data. To make the demo as accessible as possible, we synthesise the
[1% Teaching File for the 2011 Census](https://www.ons.gov.uk/census/2011census/2011censusdata/censusmicrodata/microdatateachingfile).

The demonstration can be found in `main.html`, and its source code is in
`main.ipynb`. If you're recreating the analysis yourself, download the data and
save it as `main.csv` in this directory. Then you can run the notebook and
render it however you please. To render it as it is here, use `nbconvert`:

```zsh
$ cd /path/to/mst-demo
$ jupyter nbconvert --to html --no-input main.ipynb --output index.html
```

Requirements for running the notebook are defined in `requirements.txt`. You
will need access to a C/C++ compiler and `graphviz` for the visualisations.
