# Installing ARToolkit NFT

ARToolKit NFT is supplied as prebuilt binaries, with source code for examples and some of the utilities.

## Installation

### Windows

Choose the appropriate package based on your system type and compiler.

-   ARToolKit NFT v3.50.0 Setup (bin-win32-vs90sp1) : Windows 32 bit for use with Microsoft Visual Studio 2008 SP1
-   ARToolKit NFT v3.50.0 Setup (bin-win32-vs100) : Windows 32 bit for use with Microsoft Visual Studio 2010

Double-click the installer and follow the prompts. ARToolKit NFT is installed into the "Program Files" folder on your main drive, and entries are also created in the start menu.

The installer automatically sets the ARTOOLKIT_NFT_ROOT environment variable to point to your installation.

### Mac OS X

The package ARToolKitNFT-bin-3.50.0-MacOSX-Universal.tar.gz can be placed wherever so desired and double-clicked to unpack. Typically, it is placed alongside the ARToolKit Professional folder. Mac OS X 10.5 or later is required.

After installation, run the script "share/artoolkitnft-setenv" in your terminal. This sets the ARTOOLKIT_NFT_ROOT environment variable for csh/tsch/sh/bash and Mac OS X GUI-based applications launched from the Finder.