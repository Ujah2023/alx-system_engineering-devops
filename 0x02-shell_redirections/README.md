find -type f -name "*.git" | rev | cut -d "/" -f 1 | cut -d '.' 2- | rev | LC_ALL=C sort -f lists all the files with a .gif extension in the current directory and all its sub-directories.

Hidden files should be listed

Only regular files (not directories) should be listed

The names of the files should be displayed without their extensions

The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay)

One file name per line

The listing should end with a new line
