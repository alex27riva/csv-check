csv-check
=========

Is an ultra light command line tool to check that a csv file matches [RFC 4180](https://www.ietf.org/rfc/rfc4180.txt) format.

It reads from standard in and writes to standard error. It will exit on the first error encountered.

Build:
	go build -o csv-check main.go

Usage: 

	csv-check myfile.csv

