0-iam_betty contains a script that switches the current user to the user betty
1-who_am_i is a script that prints the effective username of the current user
2-groups is a script that prints all the groups the current user is part of
3-new_owner is a script that changes the owner of file hello to the user betty
4-empty is a script that creates empty file hello
5-execute adds execute permission to the owner of file hello
6-multiple_permission adds execute permission to the owner and group owner and adds read permission to the other users
7-everybody add execute permission to owner, group owner and user
8-jams_bond gives no permission to the owner and group except others
9-john_doe sets the mode of the file hello to -rwxr-x-wx 1 julien julien 23 sep 20 14:25 hello
10-mirror_permission sets the mode of the file hello to olleh
11-directories_permission adds execute permissions to all the owners, group owners and all other users
12-directory_permission creates a directory called my_dir with 751permissions in the working directory
13-change_group changes the group owner to school for file hello