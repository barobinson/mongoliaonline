# Tutorials for Mongolia online learning

This package contains the following tutorials:
 - [Reading in data](inst/tutorials/readindata/readindata.Rmd)
 - [Manipulating data](inst/tutorials/manipulating.Rmd)

The material is adapted from workshop material created by Julian Faraway.

## Running the tutorials

Download and install the package mongoliaonline and run

`learnr::run_tutorial("name_of_tutorial", package = "mongoliaonline")`

to run the tutorial with name `name_of_tutorial`.

## Test tutorial

This package also contains only a test tutorial, which includes:
 - Demonstration of embedding a YouTube video
 - Hello, Tutorial! copied from user manual for learnr showing how coding exercises work

To run the test tutorial, download and install the package mongoliaonline and run

`learnr::run_tutorial("test", package = "mongoliaonline")`.
