# Linux From Scratch
Let's get this!

Some notes from problems I've run into so far have been running "make install"

So, in chapter 5 when installing binutile I need to be added to sodoers as followed.

# Members of the admin group may gain root privileges
%admin ALL=(ALL) ALL
%lfs ALL=(ALL) NOPASSWD:ALL


# Allow members of group sudo to execute any command
%sudo	ALL=(ALL:ALL) ALL
%lfs	ALL=(ALL:ALL) ALL

