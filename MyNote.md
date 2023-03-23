# files and folders commands

```bash
# this print the current directory
pwd

# pushd with popd works better than the cd command
pushd <NAME OF THE DIRECTORY>
# then by the command popd it returns to the previous dir
popd

# wildcard: search for all files ending with .md
ls *.md
# the question mark match with e.g. one unknown character
ls *.?d
# returs all upper case characters 
ls [[:upper:]]*

# whereis doen't exist in Windows git bash
# this command tries to find sth in the directory
whereis THEFILE
which
find

# make a dir
mkdir DIRNAME

# make a file
touch FILENAME

# move a file or a directory
mv SOURCEPATH DESTPATH

# copy a file or dircetory
cp SOURCE DESTINATION

# remove a file or dircetory, it could get wildcard as well for dir needs -r
rm PATH

# remove a dir
rmdir PATH
```

# File contents

```bash
# cat stands for concatenation
cat FILEPATH

# cat also concatenate different files
cat FILE1 FILE2

# to get information from a log file (long text file):
head -n NUMBERofLINES FILENAME
tail -n NUM FILENAME # the last n lines 

more FILENAME
less FILENAME # press h for help, q to exit


# grep finds text inside the files
grep PATTERN FILE
```

# Environment Variables
```bash
# to see all env variables
env

# to see only one specific environment variable
echo $NAME # remember the $ makr

# to make an environment variable
export newVar=VALUE # only lives during the current session
# how to make it global and long lasting:
# must be added to some files

```

# NEXT
```bash
```
