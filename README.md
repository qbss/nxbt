# nxbt
A fork and improvement of the XBT program written by Joe Collins.

**MASTER** - _Hopefully stable branch._\
**DEV** - _Development Branch (latest changes)_

## INTRODUCTION

This is somewhat of a fork of XBT, written by Joe Collins on October 4th, 2017:

https://www.youtube.com/channel/UCTfabOKD7Yty6sDF4POBVqA

http://www.ezeelinux.com/bash-scripts/

Here's the --help output, as of 4th March, 2018:

```
$ nxbt --help
            NXBT - NEW XBT (2018-03-04)
            Written by terminalforlife (terminalforlife@yahoo.com)

            A fork and improvement of the XBT program written by Joe Collins.

SYNTAX:     nxbt [OPTS] TARGET

OPTS:       --help|-h|-?            - Displays this help information.
            --version|-v            - Output only the version datestamp.
            --debug                 - Enables the built-in bash debugging.
            --quiet|-q              - Runs in quiet mode. Errors still output.
            --log|-l PATH           - Choose a different location for the logfile.
            --source|-s PATH        - Choose a different location to back up.
            --and-source|-S PATH    - Custom source to back up, with the defaults.

NOTE:       Where TARGET is the location to store the backed up files. The files
            will be stored within a timestamped directory. An example TARGET:

              nxbt /media/$USER/Backup_Drive/

FILE:       By default, errors are redirected to: /tmp/nxbt_$USER_$$.log
```

I think this is now done. Feel free to use it. I'll tweak it here and there, adding features if I can think any up. If you'd like to make any suggestions, please feel free to E-Mail me at my E-Mail address mentioned above.

Tested as working on Linux Mint 18.2 with the Mate desktop environment.

*Quoting Joe Collins from XBT, which still applies mostly here:*
> Requirements:
> 
> XBT should run on any currently supported Linux distribution with BASH. The dedicated USB drive must be formatted to a Linux native file system such as Ext4 to ensure that file permissions will be stored unchanged.
> 
> …And away we go!

## INSTALLATION

Visit the installit repository to use the easy-to-use TFL downloader.
