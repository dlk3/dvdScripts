# Inject Chapter Marks From DVD Title Into MKV

This script reads chapter metadata from the titles on a DVD and
injects it into pre-existing MKV files on disk.  The original MKV
files are preserved, with the ".bak" extension added to their names.

1)  This script is run within the diretory containing the video files.

2)  The video files are processed in sequential order starting with
    the file that is specified on the command line.

3)  The order of the titles on the DVD must match the order of the
    video files on disk.

4)  Titles on the DVD that are shorter than 30 minutes in length are
    ignored.

5)  The script depends on the lsdvd, mplayer and ffmpeg applications.
