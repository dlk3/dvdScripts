#  Scripts For Ripping TV Series DVDs

This is a collection of utility scripts I wrote to help me rip
individual TV episodes off of some DVDs I own.

* **setChapters** reads the chapter markers from the titles on a DVD and muxes them into prexisting MKV files.  I used this to update the MKVs that I downloaded for a series with chapter markers from the DVDs for the same series.  Chapter marks are time-based so they are not dependent on encoding frame rates or similar factors.

* **dvdrip** encodes the titles on a DVD as MKV files using HandBrakeCLI.  It names these files using episode names it gets from TheTVDB.com.
