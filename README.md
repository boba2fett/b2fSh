# b2fshell:~# -- Single-file PHP Shell and python CLI

b2fshell:~# is a very basic, single-file, PHP shell. It can be used to quickly execute commands on a server when pentesting a PHP application. Use it with caution: this script represents a security risk for the server.

**This is Spar.. a Fork** from [flozz/p0wny-shell](https://github.com/flozz/p0wny-shell)

**Features:**

* Command history (using arrow keys `↑` `↓`)
* Auto-completion of command and file names (using `Tab` key)
* Navigate on the remote file-system (using `cd` command)
* Upload a file to the server (usig `upload <destination_file_name>` command)
* Download a file from the server (using `download <file_name>` command)
* Auto gather files from remote server
* A degree of autamation

**WARNING:** THIS SCRIPT IS A SECURITY HOLE. **DO NOT** UPLOAD IT ON A SERVER UNTIL YOU KNOW WHAT YOU ARE DOING!

## Changelog

* **2020-06-17:** Local python interface
* **2020-07-16:** Wildcard in Path

## TODO

