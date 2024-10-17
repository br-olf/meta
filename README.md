# meta
Recursively prints the metadata of all files in a given directory.

## usage
```
usage: meta [-h] [-d DIRECTORY] [-j OUTPUT_FILE] [-m] [-q | -t]

Recursively prints the metadata of all files in a given directory.

options:
  -h, --help            show this help message and exit
  -d DIRECTORY, --directory DIRECTORY
                        The directory to start reading from. (default: './' )
  -j OUTPUT_FILE, --json OUTPUT_FILE
                        Save data as JSON. (will always export atime, mtime and ctime)
  -m, --mime            Check the files mime types (slow).
  -q, --quiet           Don't print output as text table.
  -t, --time            Also output atime, mtime and ctime.
```
