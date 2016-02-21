# rostime
ROSTIME reads log files from stdin and converts all UNIX timestamps to formatted datetimes.

## Usage
`rosdate < infile > outfile [format]`

The application reads from `stdin` and writes to `stdout`.   
A date format can optionally be specified as an argument; otherwise timestamps will be
converted to ISO 8601 format.

## History
February 20, 2016: Version 1, Initial release.

## License
Copyright (c) 2016, Yvan Rodrigues. All rights reserved.  
This software is distributed under the terms of the New BSD License.  
https://en.wikipedia.org/wiki/BSD_licenses
