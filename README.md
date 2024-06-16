# oracle-scripts
Shell scripts for Unix/Linux must run on AIX 7 as well as latest Linux.
Windows is not covered.

These scripts are designed to work in an environment having diverse Oracle database versions and diverse Operating Systems.

## Programming
The key principle for these scripts is compatibility. POSIX level. 

Shell will be used, ksh compatible shell! C and Perl are not excluded.

No fancy bash-isms, no gnu tools. Expect awk, sed, and ex. 

## Setup
/oracle/scripts/ will contain the scripts and possible configuration files. 

System and server related scripts will be pushed in /usr/local/bin/

## Naming
Still a wip. 

The scripts shall have no extension, should the scripting language change to perl for example.
