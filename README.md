# Bash Commands Cheatsheet

Here is a cheatsheet I am using to remember some of the most commmon `Bash` commands.

### Navigating the file system



##### The `cd` command

This is a command that stands for `change directory` and is commonly used to navigate throughout the file system.

1. cd .. move up a directory
2. cd ~ goes back to home directory

* ex. cd Desktop


##### The `mkdir` command

This commands makes a new directory in whatever directory you are in

* `touch` makes a new file in the directory
`&&` stands for "and" , can be used to make two commands in one line 

* ex. mkdir testfolder , cd testfolder , touch test.md && cd test.md

##### The `mv` command 

can be used to move files as well as rename files 

* ex. mv ~/drawers/pjs/warm.pjs ~/drawers/pjs/summer.pjs 
(renames warm.pjs to summer.pjs)

* ex. mv ~/drawers/pjs/favorite.socks ~/drawers/socks (moves favorite.socks from pjs to socks directory)

##### The `rm` command

can be used to remove files 

* ex. cd ~/drawers/socks && rm dress.socks
(goes to socks directory and removes dress.socks)

##### The `*.` wildcard cheat

can be used to move all of the same type of files at once 

* ex. rm *.socks
(removes all .socks files)

##### The `cp` command

can be used to copy files & directories

* ex. cp *.js ~/dest-folder
(copies all .js files)

* ex. cp -R ./sample-code ~/dest-folder
(-R will copy an entire directory into another one)

## To clear history and terminal window just type in `clear` or press `cmd+k`