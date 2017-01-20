# rostime
ROSTIME reads log files from stdin and converts all UNIX timestamps to formatted datetimes.

![epoch fail](http://imgs.xkcd.com/comics/bug.png)

## Usage
`rostime < infile > outfile [format]`

The application reads from `stdin` and writes to `stdout`.   
A date format can optionally be specified as an argument, in [`strftime` format](https://docs.python.org/2/library/datetime.html#strftime-strptime-behavior); otherwise timestamps will be
converted to [ISO 8601 format](https://en.wikipedia.org/wiki/ISO_8601).

## History
February 20, 2016: Version 1, Initial release.
January 20, 2017: Version 2, `utcfromtimestamp()` is used instead of `fromtimestamp()`.

## License
Copyright (c) 2016, [Yvan Rodrigues](http://yvanrodrigues.com). All rights reserved.  
This software is distributed under the terms of the New BSD License.  
https://en.wikipedia.org/wiki/BSD_licenses
