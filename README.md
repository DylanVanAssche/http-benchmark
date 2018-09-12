# http-benchmark
A simple HTTP response time benchmark in Python 3.

## Features

- Set the amount of requests
- Save the results to a CSV file
- Show individual results
- Show progress during benchmarking to the console
- Reports any failed requests in it's report
- Automatically calculates median, average, minimum, maximum, standard deviation and variance of the response time

## Usage

### How to run

- If the script doesn't have execute permission, you should run first: `chmod a+x benchmark.py`
- Run it: `./benchmark.py https://www.duckduckgo.com -n 15 -i -o results.csv`. 

This example will fetch the website `www.duckduckgo.com` 15 times, the script will save the data to `results.csv` and print them individually to the console.
This small script has a nice builtin help function which describes each parameter that you can use (`./benchmark.py -h`).
