0-iam_betty changed current user to betty
1-who_am_i prints the effective username of the current user
2-groups prints all the groups the current user is part of
3-new_owner changes the owner of the file hello to the user betty
4-empty creates an empty file called hello
5-execute adds execute permission to the owner of the file hello
6-multiple_permissions execute permission to the owner and the group owner, and read permission to other users, to the file hello
7-everybody execution permission to the owner, the group owner and the other users, to the file hello
8-James_Bond set no permission for users and group but set all permissions for others
9-John_Doe sets the mode of the file hello to -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
10-mirror_permissions sets the mode of the file hello the same as olleh’s mode
11-directories_permissions dds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users
12-directory_permissions creates a directory called my_dir with permissions 751 in the working directory
