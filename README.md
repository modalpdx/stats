# Stats script

A school project that uses a bash script to calculate averages and medians
along rows or columns of input.

##About the script and input file:

The bash script reads an input file that has a matrix of numeric values
and, based on a command line parameter, either calculates averages and
medians across rows or down columns.

A test input file is provided in this repo.

To calculate along rows:

```
./stats -rows test_file
```

To calculate down columns:

```
./stats -cols test_file
```

##Colophon:

This script requires bash (obviously). It also requires tr and awk. These
should be available by default on most installations of Linux. It has not
been established whether or not gawk is required (instead of plain awk or
nawk) but it is assumed that any awk will work. YMMV.


##Disclaimer:

This is code from a school project. It satisfies assignment requirements
but is nowhere near as "scrubbed" as released software should be.
Security is not addressed, only functionality and no input
validation. If you use this code for anything other than satisfying your
curiosity, please keep the following in mind:

- there is no warranty of any kind (you use the code as-is)
- there is no support offered, please do not ask
- there is no guarantee it'll work, although it's not complex so it should
  work
- please do not take credit for code you did not write, especially if you
  are a student. NO CHEATING.

Thanks!
