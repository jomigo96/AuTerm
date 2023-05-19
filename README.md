# AuTerm

## Preface

Note that AuTerm is currently in the process of being forked and developed for an initial release, there is currently no code to get or application to run.

Sneek preview:
![Sneek preview](/docs/images/peek.png?raw=true)

## About

AuTerm is a cross-platform terminal utility, designed for communicating with embedded devices and systems, created in Qt 5.

## Downloading

Only source code is provided at present.

## Setup

### Windows:

Download and open the zip file, extract the files to a folder on your computer and double click 'AuTerm.exe' to run AuTerm.

If using the SSL version of AuTerm, then the Visual Studio 2015 runtime files are required which are available on the [Microsoft site](https://www.microsoft.com/en-gb/download/details.aspx?id=48145).

### Mac:

(**Mac OS X version 10.10 or later is required if using the pre-compiled binaries, as Secure Transport is built into OS X there is no non-SSL build available for OS X systems**): Download and open the dmg file, open it to mount it as a drive on your computer, go to the disk drive and copy the file AuTerm to folder on your computer. You can run AuTerm by double clicking the icon - if you are greeted with a warning that the executable is untrusted then you can run it by right clicking it and selecting the 'run' option. If this does not work then you may need to view the executable security settings on your mac.

### Linux (Including Raspberry Pi):

Download the tar file and extract it's contents to a location on your computer, this can be done using a graphical utility or from the command line using:

	tar xf AuTerm_<version>.tar.gz -C ~/

Where '\~/' is the location of where you want it extracted to, '\~/' will extract to the home directory of your local user account). To launch AuTerm, either double click on the executable and click the 'run' button (if asked), or execute it from a terminal as so:

	./AuTerm

Before running, you may need to install some additional libraries, please see https://github.com/LairdCP/AuTerm/wiki/Installing for further details. You may also be required to add a udev rule to grant non-root users access to USB devices, please see https://github.com/LairdCP/AuTerm/wiki/Granting-non-root-USB-device-access-(Linux) for details.

## Help and contributing

Users are welcome to open issues and submit pull requests to have features merged. PRs should target the `develop` branch.

## Speed/Throughput testing

There is a quick guide available giving an overview of the speed testing feature of AuTerm, https://github.com/LairdCP/AuTerm/wiki/Using-the-Speed-Test-feature

## Compiling

For details on compiling, please refer to [the wiki](https://github.com/LairdCP/AuTerm/wiki/Compiling).

## License

AuTerm is released under the [GPLv3 license](https://github.com/LairdCP/AuTerm/blob/master/LICENSE).
