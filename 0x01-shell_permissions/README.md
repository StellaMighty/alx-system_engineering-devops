su betty This script switches the current user to the user betty
id -un This script prints the effective username of the current user
groups This script that prints all the groups the current user is part of
chown betty hello This changes the owner of the file hello to betty
touch hello THis creates an empty file called hello
chmod u+x hello  This script adds execute permission to the owner of the file hello
chmod u+x, g+x, o+r hello   This adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
chmod ugo+x hello   This adds exection command to everybody
chmod 007 hello   This grants access only to the other users
chmod 753 hello   This sets the permission of owner, group and others
chmod --reference==olleh hello This mirrors the permissions in file olleh to hello
chmod -R +X .   This adds execute permission to all subdirectories of the current directory
mkdir -m 751 my_dir   This creates a directoryin a parent directory
chgrp school hello   this changes the group owner to school for the file hello
chown vincent:staff *    changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
chown -h vincent:staff _hello   script that changes the owner and the group owner of _hello to vincent and staff respectively.
chown --from=gumiea betty hello changes the owner of the file hello to betty only if it is owned by the user guillaume.
telnet towel.blinkenlights.nl	 play the StarWars IV episode in the terminal.
