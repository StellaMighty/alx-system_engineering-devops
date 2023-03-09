su betty This script switches the current user to the user betty
id -un This script prints the effective username of the current user
groups This script that prints all the groups the current user is part of
chown betty hello This changes the owner of the file hello to betty
touch hello THis creates an empty file called hello
chmod u+x hello  This script adds execute permission to the owner of the file hello
chmod u+x, g+x, o+r hello   This adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
chmod ugo+x hello   This adds exection command to everybody
chmod 007 hello   This grants access only to the other users
