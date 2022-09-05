# Shell Redirections


### [0-hello_world](./0-hello_world)
```
echo "Hello, World"
print's "Hello World to the standard output
```


### [1-confused_smiley](./1-confused_smiley)
```
echo "\"(Ôo)'"
prints "(Ôo)' to the screen. \" is used to escape "
```


### [2-hellofile](./2-hellofile)
```
cat /etc/passwd
displays the contents of the passwd file
```


### [3-twofiles](./3-twofiles)
```
cat /etc/passwd /etc/hosts
displays the contents of the two files
```


### [4-lastlines](./4-lastlines)
```
tail /etc/passwd
the tail command displays the last ten lines of a file
```


### [5-firstlines](./5-firstlines)
```
head /etc/passwd
the head command displays the first 10 lines of a file
```


### [6-third_line](./6-third_line)
```
head -3 iacta
this command prints the third line of the file iacta
```


### [7-file](./7-file)
```
echo "Best School" > "\*\\\'\"Best School\"\'\\\*$\?\*\*\*\*\*:)"
creates a file named \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) with the contents "Best School"
```


### [8-cwd_state](./8-cwd_state)
```
ls -la > ls_cwd_content
writes the result of the ls -la command to the file ls_cwd_content
```


### [9-duplicate_last_line](./9-duplicate_last_line)
```
tail -1 iacta >> iacta
gets the last line of the iacta file and appends to the same file
```


### [10-no_more_js](./10-no_more_js)
```
find . -type f -name "*.js" -delete
finds and deletes all files with extension .js
```


### [11-directories](./11-directories)
```
find . -type d ! -path . -print | wc -l
finds all directories and sub directories prints the count
```


