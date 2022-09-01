# Shell Permissions 

Manipulating file permission in linux

### [0-iam_betty](./0-iam_betty) 
```
su betty
the su <username> command is used to change user 
```

### [1-who_am_i](./1-who_am_i)
```
whoami
the whoami command is used to print the username of the current user
```

### [2-groups](./2-groups)
```
groups
Lists all the groups the current user is part of
```

### [3-new_owner](./3-new_owner)
```
chown betty hello
change the owner of  file "hello" to user "betty"
```

### [4-empty](./4-empty)
```
touch hello
creates an empty named hello
```

### [5-execute](./5-execute)
```
chmod u+x hello
adds execute permission to the owner of the file hello
```

### [6-multiple_permissions](./6-multiple_permissions)
```
chmod ug+x, o+x
adds execute command to owner and group, and read permission to others
```

