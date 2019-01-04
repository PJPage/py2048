py2048
======

A cross-platform clone of 2048 using Python 2.7 and pygame.


## Dependencies

### LINUX

You may not have to install Python, as it is installed by default with most
Linux distros. However, if for some reason you do not have Python 2.7, package
names are included below along with pygame.

Arch: `sudo pacman -Sy python2 python2-pygame`

Debian/Ubuntu: `sudo apt-get install python2.7 python-pygame`

Fedora: `sudo yum install python pygame`

### WINDOWS

[Python 2.7](https://www.python.org/ftp/python/2.7.7/python-2.7.7.msi),
[pygame](http://pygame.org/ftp/pygame-1.9.1.win32-py2.7.msi)
(direct download)

**NOTE:** Since pygame only comes in 32-bit, the linked version of Python is
also 32-bit. A 64-bit installation of Python will not work with pygame.

### MAC OS X

None of the project developers have access to a Mac, so we cannot support macOS.
However, since Python 2 and pygame are both available for macOS, the game should
theoretically run, since we do not currently have any platform-specific code.

## Running the Game

Once you have this repository cloned or downloaded, run `main.py` from the project root.

### Extra Feature(s)

You can change the size of the playfield by inputting two numbers as arguments on the command line.
This is optional. However, both must be present to affect the size.

USAGE:

    python main.py [board_width] [board_height]

Press `A` to initiate "Auto Mode!" Watch as the game plays itself for you!
