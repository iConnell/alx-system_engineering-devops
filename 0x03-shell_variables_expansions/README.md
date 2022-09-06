# Shell Variables Expansions


### [0-alias](./alias)
```
alias ls='rm *'
creates an alias of the rm command named ls
```


### [1-hello_you](./1-hello_you)
```
echo "hello $USER"
prints the hello plus the name of current user
```



### [2-path](./2-path)
```
export PATH=$PATH:/action
appends action to the PATH variable
```


### [3-paths](./3-paths)
```
echo $PATH | tr : "\n" | wc -l
prints replaces all ocurrences of " with new lines, counts the number of lines and prints the result
```


### [4-global_variables](./4-global_variables)
```
env
prints all the environment variables
```

