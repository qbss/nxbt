# nxbt
A fork and improvement of the XBT program written by Joe Collins.

INTRODUCTION
------------

This is somewhat of a fork of XBT, written by Joe Collins on October 4th, 2017:

https://www.youtube.com/channel/UCTfabOKD7Yty6sDF4POBVqA
http://www.ezeelinux.com/bash-scripts/

I think this is now done. Feel free to use it. I'll tweak it here and there, adding features if I can think any up. If you'd like to make any suggestions, please feel free to E-Mail me at my E-Mail address mentioned above.

Tested as working on Linux Mint 18.2 with the Mate desktop environment.

*Quoting Joe Collins from XBT, which still applies mostly here:*
> Requirements:
> 
> XBT should run on any currently supported Linux distribution with BASH. The dedicated USB drive must be formatted to a Linux native file system such as Ext4 to ensure that file permissions will be stored unchanged.
> 
> …And away we go!


INSTALLATION
------------

Download and use the `install_nxbt` installer by using this terminal command:

```bash
wget -q https://raw.githubusercontent.com/terminalforlife/nxbt/master/install_nxbt
```

Now execute the installer with this:

```bash
sudo bash install_nxbt
```

Or if you prefer, make it executable, then more easily run it like so:

```bash
chmod u+x install_nxbt
./install_nxbt
```

Example installation of nxbt:

    ➤  chmod u+x install_nxbt
    ➤  sudo ./install_nxbt
    L096: Checking conflict: /usr/bin/nxbt
    L108: Downloading here: /usr/bin/nxbt
    L112: Correcting attributes: /usr/bin/nxbt

Example uninstallation of nxbt:

    ➤  sudo ./install_nxbt --uninstall
    L087: Uninstalling program.
    L118: Sending to trash: /usr/bin/nxbt
