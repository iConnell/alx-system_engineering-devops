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


### [8-true_knowledge](./8-true_knowledge)
```
echo $((128 + $TRUEKNOWLEDGE))
adds 128 to the value of the TRUEKNOWLEDGE variable
```


### [9-divide_and_rule](./9-divide_and_rule)
```
echo $(($POWER/$DIVIDE)
divides the power variable by the divide variable
```


### [10-love_exponent_breath](./10-love_exponent_breath)
```
echo $(($BREATH**$LOVE))
raises the BREATH variable to the power LOVE variable
```


### [11-binary_to_decimal](./11-binary_to_decimal)
```
echo $((2#$BINARY))
converts the binary value of BINARY variable to base 10
```


### [12-combinations](./12-combinations)
```
echo {a..z}{a..z} | tr " " "\n" | grep -v "oo"
{a..z}{a..z} creates a combination of all letters from a to z
and passes to the tr command with replaces all white spaces with newline character
which is finally passed to the grep command whith uses invert matching to select all lines that do not match the argument "oo"
```

