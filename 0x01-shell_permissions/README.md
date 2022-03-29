# 0x01-shell_permissions

This directory contains some scripts on shell, permissions

## script files

* 0-iam_betty

    > This script switches the current user to the user `betty`

* 1-who_am_i

    > Script that prints the effective username of the current user

* 2-groups

    > This script prints all groups the current user is part of

* 3-new_owner

    > A script that changes the owner of the file `hello` to the user `betty`
    
* 4-empty

    > Script that creates an empty file called `hello`
    
* 5-execute

    > This script adds execute permission to the owner of the file `hello`

* 6-multiple_permissions

    > Script that adds execute permission to the owner and the group owner, and read permission to other users. to the file `hello`
    >
    > The file is the working directory

* 7-everybody

    > A script that adds execute permission to the owner, the group owner and the other users, to the fle `hello`
    >
    > The file is the working directory
    >
    > No commas are used in the script

* 8-James_Bond

    > This script sets the permission to the file `hello` as follows:
    >
    > * Owner: no permission at all
    > * Group: no permission at all
    > * Other usersL all the permissions
    >
    > File is the working directory
    >
    > No commas are used in the script

* 9-John_Doe

    > A script that sets the mode of the file `hello` to this:
    >
    > ```-rwxr-x-wx 1 julien 23 sep 20 14:25 hello```
    >
    > File is the working directory
    >
    > No commas are used in the script

* 10-mirror_permissions

    > Script that sets the mode of the file `hello` the same as `olleh`'s mode
    >
    > Both files are in the working directory

* 11-directories_permissions

    > This script adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users
    >
    > Regular files are not to be changed

* 12-directory_permissions

    > Script that creates a directory called `my_dir` with permissions 751 in the working directory

* 13-change_group

    > A script that changes the group owner to `school` for the file `hello`
    >
    > File is in the working directory

* 100-change_owner_and_group

    > This is a script that changes the owner to `vincent` and the group owner to `staff` for all the files and directories in the working directory

* 101-symbolic_link_permissions

    > A script that changes the owner and the group owner of `_hello` to `vincent` and `staff` respectively
    >
    > File is a symbolic link and in the working directory

* 102-if_only

    > Script that changes the owner of the file `hello` to `betty` only if it is owned by the user `guillaume`
    >
    > File is the working directory

* 103-Star_Wars

    > This is a script that plays the StarWars IV episode int he terminal
