find . -empty | rev | cut -d '/' -f 1 | rev finds all empty files and directories in the current directory and all sub-directories.

Only the names of the files and directories should be displayed (not the entire path)

Hidden files should be listed

One file name per line

The listing should end with a new line
