# StratLoggerPlot
## Plot a Striplog from a StratLogger CSV

Basically, this is a wrapper of 'striplog' https://github.com/agile-geoscience/striplog

Uses csv format exported by "StratLogger," an Android app for quick-logging stratigraphic sections that was developed at Colorado School of Mines https://github.com/jcliang001/Stratlogger


This notebook takes outputs from Radiation Solutions Model RS 125 handheld gamma ray spectrometer and:
1. makes sure the data looks good
1. calculates API GR value based on REF
1. makes a plot to export to put next to a graphic log of an outcrop
1. allows export of an LAS file to import into Petrel

## The main file to modify is `HandheldGammaRayPlotter.ipynb`

A csv example of a data file is provided - "assay_2263_FakeHeights.csv". This is real data from the Cloridorme Formation, Canada.
