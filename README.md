# Legion Performance Data

This repository contains raw performance data gathered for Legion and
applications using Legion.  It represents the middle piece of the overall
Legion performance tracking model described [somewhere](http://).

Everything in this repository is "raw data" - all the smarts for querying
and presenting data is over [here](https://github.com/StanfordLegion/perf-frontend).

The data in this repository is structured as follows:
  * benchmarks/...: JSON files that define benchmarks.  Directory hierarchy
              may be used to group benchmarks as desired.

  * measurements/...: JSON files that contain measurements.  The names of
              these files have no meaning to the querying tools, and should
              include some sort of UUID to avoid name collisions.  In general,
              a measurement file should not be modified once added to the
              respository.

## Benchmark Schema

TBD

## Measurement Schema

TBD
