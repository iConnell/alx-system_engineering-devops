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
chmod 754 hello
adds execute permission to owner and group, and read permission to others
```

### [7-everybody](./7-everybody)
```
chmod a+x hello
adds execute permission to everybody
```

### [8-James_Bond](./8-James_Bond)
```
chmod 007 hello
adds full permissions to other users but none to owner and group
```

### [9-John_Doe](./9-John_Doe)
```
chmod 753 hello
adds full permissions to the owner, read and execute permissions for user group and write and execute to other users
```

### [10-mirror_permissions](./10-mirror_permissions)
```
chmod --reference=olleh hello
adds the same exact permissions as the file olleh to the file hello
```

