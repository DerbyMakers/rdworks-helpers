# rdworks-helpers

RDWorks is commonly used for controlling cheap Chinese laser cutters. It's feely downloadable from the manufacturer's [web site]() but it's only available for Windows. It will run under Wine on linux, and reportedly also on Macs, with a few quirks. 

## Installation

[Winetricks](https://wiki.winehq.org/Winetricks) is a tool to make it easier to install Windows programs on linux. It doesn't have a built in script for installing RDWorks yet, but you can try this one. So far it's only been tested with stock wine and winetricks on Ubuntu 17.10, but should work with other versions and distros. It might even work with Macs.

    winetricks rdworksv8.verb

RuiDa's download site is slow, and winetricks sometimes gives up fetching the file. If that happens you can download manually and put the file                                                                                                                                            in its cache directory before rerunning the command above.
