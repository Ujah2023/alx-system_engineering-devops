echo $((`echo $PATH | grep -o ":/" | wc -l`+ 1)) counts the number of directories in the PATH
