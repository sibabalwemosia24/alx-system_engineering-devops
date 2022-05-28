su betty- switches current userto ther user betty
whoami- prints effective username of current user
groups- prints all groups current user is part of
sude chown betty hello- changes owner of file hello to user betty
touch hello- creats emptly file hello
chmod u+x hello- adds execute permissions to owner of file hello
chmod ug+x,o+r hello- adds execution permission to owner and group, and read permission to other users, to file hello
chmod a+x hello- adds execution permissionfor everyone
chmode 007 hello- give no permission to owner, no permission to group and all permissions to other users
chmod 753 hello
chmod --reference=olleh hello- sets mode of file hello the same as olleh
chmod a+X*- adds execution permission to all sub dir in current dir
mkdir -m 751 my_dir- creates my_dir dir with permissions 751
