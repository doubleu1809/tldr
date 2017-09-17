# sdiff

> Compares two files to find differances and interactivly merges them. Without the -o option, sdiff behaves like diff-side-by-side.

- Treat all files as text files. Useful for checking to see if binary files are identical:

`sdiff -a`

- Ignore repeating blanks and end-of-line blanks; treat successive blanks as one:

`sdiff -b`

- Ignore blank lines in files:

`sdiff -B`

- Ignore segments of numerous changes and output a smaller set of changes:

`sdiff -d`

- Speed output of large files by scanning for scattered small changes; long stretches with many changes may not show up:

`sdiff -H`

- Ignore case in text comparison. Upper- and lowercase are considered the same:

`sdiff -i`
