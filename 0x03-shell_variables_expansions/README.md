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


### [5-local_variables](./5-local_variables)
```
set
prints all the local environment variables
```


### [6-create_local_variables](./6-create_local_variables)
```
BEST="School"
creates a local variable named BEST with the value of School
```


### [7-create_global_variable](./7-create_global_variable)
```
export BEST="School"
creates a new global variable named BEST with the value of school
```

