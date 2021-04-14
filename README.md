# SIMPLE SHELL
## Description
Shell is an environment in which we can run our commands, programs, and shell scripts.There are different flavors of a shell,
just as there are different flavors of operating systems.Each flavor of shell has its own set of recognized commands and functions.
## FILES
project is created with:
* File1:
* File 2:
* File 2:
## Requirments
simple_shell is designed to run in the Ubuntu linux environment and to be compiled using the GNU compiler collection v. gcc 4.8.4
with flags -Wall, -Werror, -Wextra, and -pedantic.
## Installation
* clone this repostory https://github.com/kalkidan999/simple_shell.git
* Change directories into the repository: acd simple_shell
* Compile: gcc -Wall -Werror -Wextra -pedantic *.c -o hsh
* Run the shell: ./hsh
## Example
### 1.
$ ./hsh <br />
$ pwd <br />
/home/username/ <br />
$ ^D <br />
### 2. 
$ ./hsh <br />
$ ls -l /tmp <br />
-rw------- 1 username username    0 Dec  5 12:09 config-err-aAMZrR <br />
drwx------ 3 root   root   4096 Dec  5 12:09 systemd-private-062a0eca7f2a44349733e78cb4abdff4-colord.service-V7DUzr <br />
drwx------ 3 root   root   4096 Dec  5 12:09 systemd-private-062a0eca7f2a44349733e78cb4abdff4-rtkit-daemon.service-ANGvoV <br />
drwx------ 3 root   root   4096 Dec  5 12:07 systemd-private-062a0eca7f2a44349733e78cb4abdff4-systemd-timesyncd.service-CdXUtH <br />
-rw-rw-r-- 1 username username    0 Dec  5 12:09 unity_support_test.0 <br />
$ ^D <br />
$
### 3.
run the program by executing the follwing command <br />
$ ./hsh <br />
$ ls
## List of functions and system calls we are allowed to use:
access (man 2 access) <br />
chdir (man 2 chdir) <br />
close (man 2 close)<br />
closedir (man 3 closedir)<br />
execve (man 2 execve)<br />
exit (man 3 exit)<br />
fork (man 2 fork)<br />
free (man 3 free)<br />
fstat (man 2 fstat)<br />
getcwd (man 3 getcwd)<br />
getline (man 3 getline)<br />
kill (man 2 kill)<br />
lstat (man 2 lstat)<br />
malloc (man 3 malloc)<br />
open (man 2 open)<br />
opendir (man 3 opendir)<br />
perror (man 3 perror)<br />
read (man 2 read)<br />
readdir (man 3 readdir)<br />
signal (man 2 signal)<br />
stat (man 2 stat)<br />
strtok (man 3 strtok)<br />
wait (man 2 wait)<br />
waitpid (man 2 waitpid)<br />
wait3 (man 2 wait3)<br />
wait4 (man 2 wait4)<br />
write (man 2 write)<br />
_exit (man 2 _exit)<br />
## Authors
* Kalkidan Demes
* Fkadeal Matiwos
