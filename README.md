# safeplace
This is a little password manager. Its written in bash and use GNU GPG to
encrypt the passwords with AES256. 
You need the following programms: GNU GPG and apg (the latter for password
generation). Both should be available in the repositories of your distro.

# Features
Below are just a few features of this very very comprehensive script!

## Keep it in clipboard
Most of the time you don't want to print your password on stdout, because
you want it to be entered in a password promt somewhere else. By default the
script saves your password for 20 seconds in the clipboard. Enough time for you
to paste it in the password promt.

## Auto generated passwords
If you are to lazy to think out a crazy password you can let the script to this
part. By default it generates a 

# Installation
Copy the script to a directory in your $PATH or type make install (for the very
lazy ones). By default your passwords are stored in your home directory in a
file called .passwords.gpg. To change this use the config command provided by
the script.

For more help type safaplace help.
