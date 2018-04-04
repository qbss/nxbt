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
            NXBT - NEW XBT (2018-04-04)
            Written by terminalforlife (terminalforlife@yahoo.com)

            A fork and improvement of the XBT program written by Joe Collins.

SYNTAX:     nxbt [OPTS] TARGET

OPTS:       --help|-h|-?            - Displays this help information.
            --version|-v            - Output only the version datestamp.
            --quiet|-q              - Runs in quiet mode. Errors still output.
            --debug|-D              - Enables the built-in bash debugging.
            --log|-l PATH           - Choose a different location for the logfile.
            --source|-s PATH        - Choose a different location to back up.
            --and-source|-S PATH    - Custom source to back up, with the defaults.

NOTE:       Where TARGET is the location to store the backed up files. The files
            will be stored within a timestamped directory. An example TARGET:

              nxbt /media/$USER/Backup_Drive/

FILE:       By default, errors are redirected to: /tmp/nxbt_*.log
```

This is functional, but still needs a little TLC. If you'd like to make any suggestions, please feel free to E-Mail me at my E-Mail address mentioned above.

Tested as working on Linux Mint 18.2 with the Mate desktop environment.
Tested as working on Ubuntu 16.04.4 with a non-standard setup.

*Quoting Joe Collins from XBT, which still applies mostly here:*
> Requirements:
>
> XBT should run on any currently supported Linux distribution with BASH. The dedicated USB drive must be formatted to a Linux native file system such as Ext4 to ensure that file permissions will be stored unchanged.
>
> …And away we go!

## INSTALLATION

Visit the installit repository to use the easy-to-use TFL downloader.
