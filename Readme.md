# Delete old files

Very simple Python script to search a directory and delete all but the newest files.

Takes a quoted path and an optional number of files to delete.

Usage:

    delete_files '/path/to/files/pre_*.ext' <num_to_keep default=3>

    e.g. delete_files '/home/boggins/pictures/*.jpg' 5

To show help:
    delete_files -h

