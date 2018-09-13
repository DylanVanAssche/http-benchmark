# http-benchmark
[![Build Status](https://travis-ci.com/DylanVanAssche/http-benchmark.svg?branch=master)](https://travis-ci.com/DylanVanAssche/http-benchmark)

A simple HTTP response time benchmark in Python 3.

## Features

- Set the amount of requests (default=20)
- Save the results to a CSV file
- Show individual results
- Show progress during benchmarking to the console
- Reports any failed requests in it's report
- Automatically calculates median, average, minimum, maximum, standard deviation and variance of the response time

## Usage

### How to run

- If the script doesn't have execute permission, you should run first: `chmod a+x benchmark.py`
- Run it: `./benchmark.py https://graph.irail.be/sncb/connections -n 5 -i -o results.csv`. 

This example will fetch the website `https://graph.irail.be/sncb/connections` 5 times, the script will save the data to `results.csv` and print them individually to the console.
This small script has a nice builtin help function which describes each parameter that you can use (`./benchmark.py -h`).
