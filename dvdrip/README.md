#  Rip TV Series DVDs

This script will extract each DVD title that is longer than 30 minutes.

The titles will be extracted as MKV files and will be given names made up of:

1)  The series name entered at the top of the script.

2)  The season and episode strings that are entered on the command line in the format SnnEnn,

3)  The episode names that we look up at thetvdb.com using the series id number given in the script.

The MKV files will be written in the current directory.

This script depends on the lsdvd and HandBrakeCLI applications.
