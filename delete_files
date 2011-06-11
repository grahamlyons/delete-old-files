from operator import itemgetter, attrgetter
import glob, os

# The directory (and optionally the file extension/pattern) to search.
#fpath=""

# The number of files to keep.
keep = 3

fileDir=glob.glob(fpath)

# Get the last modification time for each of the files.
fileData = {}
for fname in fileDir:
	fileData[fname] = os.stat(fname).st_mtime

# Sort the files according to the last modification time.
sortedFiles = sorted(fileData.items(), key=itemgetter(1))

# Keep the latest files (number defined at the top of the file, 
# so loop over a range of the number of files minus the number we're keeping.
delete = len(sortedFiles) - keep
for x in range(0, delete):
	os.remove(sortedFiles[x][0]