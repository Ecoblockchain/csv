# CSV
An Open Pipe Kit compliant command for working with CSV. Right now you can push data into a CSV.

```
# Get something to pull data from.
$ git clone https://github.com/openpipekit/rpi-cpu-temperature.git
$ ./rpi-cpu-temperature/install

# Get the CSV command to push data into a CSV file. 
$ git clone https://github.com/openpipekit/csv.git
$ ./csv/install

# Collect some data.
$ ./rpi-cpu-temperature/pull | ./csv push --file data.csv
$ ./rpi-cpu-temperature/pull | ./csv push --file data.csv
$ ./rpi-cpu-temperature/pull | ./csv push --file data.csv

# Check out the data.
$ cat data.csv
raspberry-pi-cpu-temperature
89
90
89
```

