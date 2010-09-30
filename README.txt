/**
 * Date: 2010-09-30
 * Author: Graham Lyons
 * Description: Very simple Python script to search a directory and delete all but the newest files.
 *
 */

The 'fpath' variable needs to be filled in with the path to search. A file pattern can also be included:
e.g. fpath="/Users/fred/backup/" OR fpath="/Users/fred/backup/*.tar"

The 'keep' variable just needs the number of files from the found set that you want to keep:
e.g. keep=3